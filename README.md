```
from typing import List, Dict

class COuyang24:

  def __init__(self):
    self.username: str = "couyang24"
    self.full_name: str = "Chengran (Owen) Ouyang"
    self.languages: List[str] = ["Mandarin", "English", "Python", "SQL"]
    self.company: str = "Quora"
    self.job: str = "Senior Data Scientist"
    self.motto: str = "The opposit of success is not failure. It is ........ you never try"
    self.connect: Dict[str, str] = {
                          "Kaggle": "https://www.kaggle.com/couyang", 
                          "LinkedIn": "https://www.linkedin.com/in/owenouyang/",
                          "Website": "https://couyang24.github.io/"
                          }
    
  def __str__(self):
    return f"Hello there. I'm {self.full_name} 👋"


if __name__ == "__main__":
  me = COuyang24()
```



```
from . import COuyang24
Display(COuyang24().motto)
```

![loading](https://i.imgur.com/BjBJv1Q.gif)
