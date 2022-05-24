# Who am I
I am an IB student and a security analyst. I hunt for bugs in big companies on HackerOne. Here is my profile: https://hackerone.com/dimondev

# Description
This is a free version of Turnitin. Probably the best tool for IB students.
Written in Python.

It is pretty easy to set it up:

```
pip install pyfiglet
python turnitin.py
```

Then, the screen should look like this. Pretty straightforward, just input your text and the magic happens in the backend.

```
 _____                 _ _   _
|_   _|   _ _ __ _ __ (_) |_(_)_ __
  | || | | | '__| '_ \| | __| | '_ \
  | || |_| | |  | | | | | |_| | | | |
  |_| \__,_|_|  |_| |_|_|\__|_|_| |_|


[?] Input text to check with Turnitin > 
```

Then, wait about 30 seconds and check the results, here is a sample:

```
 _____                 _ _   _
|_   _|   _ _ __ _ __ (_) |_(_)_ __
  | || | | | '__| '_ \| | __| | '_ \
  | || |_| | |  | | | | | |_| | | | |
  |_| \__,_|_|  |_| |_|_|\__|_|_| |_|


[?] Input text to check with Turnitin > It is a shame for a man to grow old without seeing the beauty and strength of which his body is capable.

[!] Word count : 22

[!] Turnitin index : 72.0

[!] Matches : [{'url': 'https://evanandretti.medium.com/was-socrates-even-shredded-9e47cddd0e5', 'percent': '72.0', 'highlight': [['0', '15']]}, {'url': 'https://www.goodreads.com/quotes/607547-no-man-has-the-right-to-be-an-amateur-in', 'percent': '72.0', 'highlight': [['0', '15']]}, {'url': 'https://forum.wordreference.com/threads/socrates-quote-on-body-fitness-in-original-greek.2775525/', 'percent': '72.0', 'highlight': [['0', '15']]}, {'url': 'https://vk.com/wall553623575_7', 'percent': '72.0', 'highlight': [['0', '15']]}, {'url': 'https://victor-mochere.com/best-quotes-from-socrates', 'percent': '72.0', 'highlight': [['0', '15']]}, {'url': 'http://www.arcane-alchemy.com/blog/2020/6/24/pagan-vs-christian-worldview-4-huge-differences', 'percent': '72.0', 'highlight': [['0', '15']]}, {'url': 'https://www.azquotes.com/quote/668418', 'percent': '59.8', 'highlight': [['4', '15']]}, {'url': 'https://www.reddit.com/r/quotes/comments/3i4xkg/it_is_a_shame_for_a_man_to_grow_old_without/', 'percent': '28.0', 'highlight': [['11', '11'], ['13', '15']]}]
```
