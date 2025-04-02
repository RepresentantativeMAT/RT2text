# RT2text
RT2text is a rule-based method that converts Representative Trajectories (RTs) into human-readable text using Regex for data extraction, aspect analysis, and Jinja2 for text generation. It structures movement patterns, identifies frequent locations, and generates fluent summaries, making mobility data more accessible and interpretable. 🚀

Dependencies:

- os;
- re;
- defaultdict class from the module collections;
- Template class from the module jinja2;
- datetime class from the module datetime;

The modules os, re, collections and datetime are all part of the Python standard library and consequently doesn't need no further installations to work. Jinja2 however needs to be downloaded:

In case you are running the file on google colab or jupiter notebook use the command:

!pip install Jinja2


