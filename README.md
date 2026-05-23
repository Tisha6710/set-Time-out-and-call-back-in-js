# set-Time-out-and-call-back-in-js

// print 1 to 10 after delay of 1 sec

function hello(){
    console.log("hello");
}
function mello(){
console.log("mello");
} 

setTimeout(hello,11*1000);
setTimeout(mello,12*1000);

// we can write set time out like this even

setTimeout(function(){
    console.log("or bhai");
},13*1000)

// print 1 to 10 after delay of 1 sec

for(let i=1;i<=10;i++){
    setTimeout(function(){
        console.log(i);

    },i*1000)
}
