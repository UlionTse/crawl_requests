**crawl_requests**
==================
*1. Feactures:*
---------------
- *crawl_requests provides api of User-Agent_pool and proxy_pool.*
- *firstly, common requests; secondly, add user-agent requests; finally, add user-agent and proxy requests.*

*2. Usage:*
-----------
>>>from crawl_requests import req,req2

>>>req.req_get(url='https://www.python.org',headers={},UA_pool=[],proxy_pool=[])

<Response [200]>

>>>rq2 = req2.Req2()

>>>rq2.all_req(method='get',url='https://www.python.org')

<Response [200]>

*3. Tips:*
----------
- *pip install crawl_requests*
- *req2 updates ua and proxy automatically.*
- *rq2 need about 10 minutes to load and test proxy to be used.*
