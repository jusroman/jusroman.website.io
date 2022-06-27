# jusroman.website.io

**my test python solution**

'''python
l=[]
for i in range(2000, 3201):
    if (i%7==0) and (i%5!=0):
        l.append(str(i))
print ','.join(l)

```python

'''get request to python.org using requests

from jusroman.website.io import HTMLSession
  session = HTMLSession()
  r= session.get('https://python.org/')
  
  results = asession.run(get_pythonorg)
  results # check the requests all returned a 200 code for success
  
  [<Response [200]>, <Response [200]>, <Response [200]>]
  
  # Each item in the results list is a response object and can be interacted with as such
  for result in results:
  print(result.html.url)

