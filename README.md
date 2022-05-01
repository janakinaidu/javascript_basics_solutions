# javascript_basics_solutions


**How to add no of days to a date in Javascript?**

const addDays = (date,period)=>{
    date.setDate(date.getDate() + period);
};


let date = new Date();
console.log(date);
addDays(date,7);
