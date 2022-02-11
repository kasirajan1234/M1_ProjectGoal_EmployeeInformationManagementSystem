# TEST PLAN
|TEST ID|TEST CASE OBJECTIVE|INPUT DATA|EXPECTED OUTPUT|ACTUAL OUTPUT|STATUS|
|:-----:|:----------------:|:---------:|:-------------:|:-----------:|:----:|
|TC_1  |for entering name |enter name: abc|abc  |abc|PASS|
|TC_2|for entering name  |entering name: abc|-|FAIL|
|TC_3|for entering age|enter age: 12|12|12|PASS|
|TC_4|for entering age|enter age: 12|12|-|FAIL|
|TC_5|for entering salary|enter salary: 5000|5000|5000|PASS|
|TC_6|for entering salary|enter salary: 5000|5000|-|FAIL|
|TC_7|for listing record|abc 12 5000|abc 12 5000|abc 12 5000|PASS|
|TC_8|for listing record|abc 12 5000|abc 12 5000|abc 5000 12|FAIL|
|TC_9|for listing record|abc 12 5000|abc 12 5000|12 abc 500|FAIL|
|TC_10|or deleting record|abc|abc|xyz|FAIL|
|TC_11|or deleting record|abc|abc|abc|PASS|
4
[poi 
gtr