# Работа с git и bash
pwd
mkdir test1
cd C:\Users\samya\test1
touch 1 2 3
ls
cd
mkdir test2
rmdir test2
cd /c/Users/samya/test1
rm 2
cd
mkdir test3
cd /c/Users/samya/test3
touch 1 2
cd
rm -r test3
cd
mkdir test4
cd /c/Users/samya/test1
mv 1 3 /c/Users/samya/test4
cd /c/Users/samya/test4
echo "line" >> 1
echo "line" >> 1
echo "line" >> 1
cat 1
echo "line" >> 3
echo "line" >> 3
echo "line" >> 3
cat 1 3
sed -i 's/.*/newline/g'


cd
pwd
mkdir test3
cd /c/Users/samya/test3
echo "row1" >> 4
echo "row2" >> 4
echo "row3" >> 4
echo "row4" >> 4
echo "row1" >> 5
echo "row2" >> 5
echo "row3" >> 5
echo "row4" >> 5
echo "row1" >> 6
echo "row2" >> 6
echo "row3" >> 6
echo "row4" >> 6
grep "row2" 5
cd
grep -r "row" test3
cd /c/Users/samya/test3
grep -c "row" 6
find /c/Users/samya/test3 -name 5
find . -name 5 -type f -delete
echo "test" > 4
echo "fail" > 4
echo "test" >> 4
ps
kill 666
ping rusau.net
ping -c 5 rusau.net
curl https://petstore.swagger.io/v2/pet/findByStatus?status=pending
curl -X 'POST' \
  'https://petstore.swagger.io/v2/pet' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{
  "id": 0,
  "category": {
    "id": 0,
    "name": "string"
  },
  "name": "doggie",
  "photoUrls": [
    "string"
  ],
  "tags": [
    {
      "id": 0,
      "name": "string"
    }
  ],
  "status": "available"
}'
