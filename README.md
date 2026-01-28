```python
from dataclasses import dataclass, field

@dataclass(frozen=True)
class DmitryDeneka:
    first_name: str = "Dmitry"
    last_name: str = "Deneka"
    motto: str = "Don’t waste time on unnecessary things!"
    
    tech_stack: list[str] = field(default_factory=lambda: [
        "Python", 
        "C/C++", 
        "MQL5", 
        "JavaScript", 
        "HTML/CSS"
    ])
```