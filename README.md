
Using HTTPie to test the API:

```bash
http :8080 message=="My name is <Type your name>"
http :8080 message=="what is my name" --it should return the name you entered

http :8080 message=="write me a summary of typescript" 
http :8080 message=="make that summary more concise. 1-2 paragraphs with no bullet points" --it should return a more concise summary about typescript, even though you did not mention typescript in the second request
```
