# boorse_bot
robot was created by js for tsetmc

## run at a spcific time 
extract by  chat.openai.com  (chatgpt)
clock time extract from os sys  
```js
// .title-r class  for  agah     .buy-btn  for exirbroker    
function runFunction() {
let timerId =setInterval(() => { document.querySelector('.title-r ').click();
}, 300);let stop = 10000;setTimeout(() => { clearInterval(timerId);   }, stop);
}

function executeAtTime(hour, minute, second) {
  const now = new Date();
  const targetTime = new Date(
    now.getFullYear(),
    now.getMonth(),
    now.getDate(),
    hour,
    minute,
    second
  );
  const timeDifference = targetTime.getTime() - now.getTime();
  
  if (timeDifference > 0) {
    setTimeout(runFunction, timeDifference);
  } else {
//current time
console.log(current time");
  }
}
// run function at spesific time
executeAtTime(8, 44, 53);
```
## agah online
```js
title-r ng-binding
let timerId =setInterval(() => { document.querySelector('.title-r').click();
}, 425);let stop = 10000;setTimeout(() => { clearInterval(timerId); alert('stop'); }, stop);	

```


## exirbroker

```js
buy mat-raised-button mat-buy

let timerId =setInterval(() => { document.querySelector('.buy.mat-raised-button.mat-buy').click();
}, 445);let stop = 10000;setTimeout(() => { clearInterval(timerId); alert('stop'); }, stop);

WAIT SECONDS=.3


buy-btn   sell-btn
let timerId =setInterval(() => { document.querySelector('.buy-btn ').click();
}, 300);let stop = 10000;setTimeout(() => { clearInterval(timerId); alert('stop'); }, stop);


oldversion
buyButton
let timerId =setInterval(() => { document.querySelector('.buyButton').click();
}, 300);let stop = 10000;setTimeout(() => { clearInterval(timerId); alert('stop'); }, stop);



2021 june
let timerId =setInterval(() => { document.querySelector('.buy-btn ').click();
}, 345);let stop = 10000;setTimeout(() => { clearInterval(timerId); alert('stop'); }, stop);

```
