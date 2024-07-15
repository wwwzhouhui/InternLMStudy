# 任务一
Python实现wordcount

代码wordcount.py

```python
import re
from collections import Counter

def word_count(text):
    # Normalize the text to lowercase and remove punctuation
    normalized_text = re.sub(r'[^\w\s]', '', text).lower()
    # Split the text into words
    words = normalized_text.split()
    # Count the occurrences of each word
    word_counts = Counter(words)
    return dict(word_counts)

input_text = """Hello world!  
This is an example.  
Word count is fun.  
Is it fun to count words?  
Yes, it is fun!"""

output = word_count(input_text)
print(output)
```

运行结果

![image-20240711225544607](https://mypicture-1258720957.cos.ap-nanjing.myqcloud.com/Obsidian/image-20240711225544607.png)

# 任务二

Vscode连接InternStudio debug笔记

![image-20240715154922189](https://mypicture-1258720957.cos.ap-nanjing.myqcloud.com/image-20240715154922189.png)

![image-20240715155510183](https://mypicture-1258720957.cos.ap-nanjing.myqcloud.com/image-20240715155510183.png)

![image-20240715155635026](https://mypicture-1258720957.cos.ap-nanjing.myqcloud.com/image-20240715155635026.png)
