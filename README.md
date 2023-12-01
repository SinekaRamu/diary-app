# Diary App

Digital diary which helps to write our dialy activities, basically the memories and feeling people will never get to understand.
let's make a autobiography.

## lesson
using html, css, javascript
here, I learned to sort the datas depends on date and reversed the date using split function.

```
function sorting() {
  const sort = myDiary.sort((a, b) => {
    return new Date(b.date) - new Date(a.date);
  });
  return sort;
}

//function to reverse the date
function reverseDate(date) {
  let d = date.split("-").reverse().join("-");
  return d;
}
```