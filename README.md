$ curl -i -x POST "http://api.box.com/2.0/group_memberships"\
-H "Authorization:Bearer<ACCESS_TOKEN>"
-H"Content-type: application/json" \
-d '{
   "user" {
   "id" "1434325"
   },
   "group":{
   "id":"4545523"
       }
       }'
