<pre>
curl "http://localhost:8000/api/posts" \
    -H 'Content-Type: application/json' \
    -u 'admin:Pass@123' \
    -d $'{
    "title": "Cool Stuff",
    "url": "http://google.com"    
 }'
 </pre>
