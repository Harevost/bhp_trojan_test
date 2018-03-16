# bhp_trojan_test
bhp github trojan by Black Hat Python


I don't know why

<p><code>
  Traceback (most recent call last):  
    File "/root/project/python/hacktools/git_trojan0.py", line 99, in <module>  
      config = get_trojan_config()  
    File "/root/project/python/hacktools/git_trojan0.py", line 45, in get_trojan_config  
      config_json = get_file_contents(trojan_config)  
    File "/root/project/python/hacktools/git_trojan0.py", line 32, in get_file_contents  
      tree = branch.commit.commit.tree.recurse()  
    File "/root/project/python/hacktools/venv/local/lib/python2.7/site-packages/github3/models.py", line 58, in \__getattr\__  
      raise AttributeError(attribute)  
  AttributeError: recurse  
</code></p>
