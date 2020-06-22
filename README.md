# what-i-learned-in-week-5

###### Joshua Londono

---

### What I Learned - Week 5
---

### Javascript

1. Terminal apps 

---

__getInput__

~~~~
function getInput(n) {
  return process.argv[n + 2];
}
~~~~

Although we've reviewed ths topic, I have a full understanding now how to get input form the command line wth args. 


__Passing Args__

~~~~
getInput(0)
~~~~

Passing arguments allows the user to interact with the app and see results.

__Passing Multiple Args__

~~~~
getInput(0) + ' ' + getInput(1)
~~~~

Passing multiple arguments allows the user to enter multple options and allows for deeper interaction with your app. 

