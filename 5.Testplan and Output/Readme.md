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
|TC_10|for deleting record|abc|abc|xyz|FAIL|
|TC_11|for deleting record|abc|abc|abc|PASS|
# OUTPUT
![Output](https://user-images.githubusercontent.com/98865218/153597615-0ffce3d2-bb72-4ec6-b44b-979af8768126.png)


