# autotoeic

This will automatically solve the problems in the toeic reading part (part5,6,7).

## Part5
Diversion of [toeicbert](https://github.com/graykode/toeicbert)．

### example

run

```
python -m toeicbert --model bert-base-uncased --file part5/test.json
```

input shape

```
{
    "1" : {
        "question" : "The music teacher had me _ scales several times.",
        "answer" : "play",
        "1" : "play",
        "2" : "to play",
        "3" : "played",
        "4" : "playing"
    },
    "2" : {
        "question" : "The music teacher had me _ scales several times.",
        "1" : "play",
        "2" : "to play",
        "3" : "played",
        "4" : "playing"
    }
}
```