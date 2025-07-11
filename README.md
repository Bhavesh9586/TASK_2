# Zaroor! Yahan aapko mil rahe hain Q1–Q18 tak ke saare MCQs (questions, options, correct answers) – clean format me, taaki aap PDF ya notebook me copy kar sako ya revise kar sako.


---

✅ Q1. Which function should be used to resolve symbolic links and return the real path of a file?

a) os.path.realpath()
b) os.path.realpath() ✅
c) os.path.exists()
d) os.readlink()


---

✅ Q2. Which method would you use to move a file from one directory to another using the shutil module?

a) shutil.copy()
b) shutil.remove()
c) shutil.move() ✅
d) shutil.transfer()


---

✅ Q3. What does this code do?

os.makedirs('folder', exist_ok=True)

a) Creates the directory 'folder'
b) Creates the directory if it doesn't exist ✅
c) Deletes and recreates the directory
d) Raises error if the folder already exists


---

✅ Q4. Which method can be used to get the size of a file in bytes?

a) os.path.getsize() ✅
b) os.getsize()
c) os.file_size()
d) os.size()


---

✅ Q5. Which of the following correctly serializes a dictionary containing non-ASCII characters into a JSON file?

a) json.dump(data)
b) json.dump(data, ensure_ascii=False) ✅
c) json.dumps(data)
d) json.dumps(data, ensure_ascii=True)


---

✅ Q6. What is the output of this code?

from datetime import datetime, timezone, timedelta
dt = datetime(2025, 3, 30, 2, 30, tzinfo=timezone.utc)
print(dt.astimezone(timezone(timedelta(hours=5, 30))))

a) 2025-03-30 03:30
b) 2025-03-30 07:30
c) 2025-03-30 08:00 ✅
d) 2025-03-30 08:30


---

✅ Q7. Which statement correctly creates a timezone-aware datetime object for IST (UTC+5:30)?

a) datetime.now(pytz.timezone('Asia/Kolkata'))
b) datetime.now().replace(tzinfo=timezone(timedelta(hours=5, 30)))
c) datetime.fromtimestamp(time.time(), timezone(timedelta(hours=5, 30)))
d) All of the above ✅


---

✅ Q8. What is the difference between datetime.now() and datetime.now(timezone.utc)?

a) datetime.now() returns naive, datetime.now(timezone.utc) returns aware ✅
b) Both are same
c) now() returns local time in UTC
d) datetime.now() is faster


---

✅ Q9. Which method should be used to parse a date string like '12-09-2025 09:30'?

a) datetime.strptime(...) ✅
b) dateutil.parser.parse(...) ✅
c) datetime.timestamp(...)
d) Both a and b ✅


---

✅ Q10. What is the result of this comparison?

from datetime import datetime, timezone
dt1 = datetime(2025, 1, 1, tzinfo=timezone.utc)
dt2 = datetime(2025, 1, 1)
print(dt1 == dt2)

a) True
b) False ✅
c) TypeError
d) ValueError


---

✅ Q11. Remove duplicates in list of dicts by 'product_id', keeping last occurrence

a) Using dictionary comprehension ✅
b) Using set with tuple items ✅
c) Using enumerate loop ✅
d) All of the above ✅


---

✅ Q12. Which expression flattens the list [[1,2],[3,4],[5]] into [1,2,3,4,5]?

a) Nested list comprehension ✅
b) sum(lst, []) ✅
c) itertools.chain(*lst) ✅
d) All of the above ✅


---

✅ Q13. What is the output of the following code?

data = [{"id": 1, "name": "A"}, {"id": 2, "name": "B"}]
result = {d["id"]: d["name"] for d in data}
print(result)

a) {'A': 1, 'B': 2}
b) {'id': 1, 'name': 'A', 'id': 2, 'name': 'B'}
c) {1: 'A', 2: 'B'} ✅
d) Error


---

✅ Q14. Convert strings to int or None from list ["1", "abc", "42"]

a) [int(x) if x.isdigit() else None for x in lst] ✅
b) [int(x) for x in lst if x.isdigit()]
c) [x if isinstance(x, str) else None for x in lst]
d) None of the above


---

✅ Q15. Filter even numbers from nested list [[1,2],[3,4],[5,6]]

a) Nested list comprehension ✅
b) filter + itertools.chain ✅
c) chain + list comp ✅
d) All of the above ✅


---

✅ Q16. Which header is used to mimic a browser in web scraping?

a) Accept-Encoding
b) Host
c) User-Agent ✅
d) Connection


---

✅ Q17. What does status code 403 represent?

a) Bad Request
b) Unauthorized
c) Forbidden ✅
d) Not Found


---

✅ Q18. Correct way to send cookies with GET request using requests

a) requests.get(url, cookies={"session_id": "abc123"}) ✅
b) requests.get(url, headers={"Cookie": "session_id=abc123"}) ✅
c) requests.get().cookies.update(...)
d) Both a and b ✅


---

Agar aap chaho to main yehi content ka final clean PDF abhi bana ke de sakta hoon — ready hoon! Batayein?

