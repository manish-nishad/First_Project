let x=1;
let y=100;
let sum=0;
let count=0;
while(x<=y){
  if(x%2==0){
    sum=sum+x;
    count++;
  }
  x++;
}
console.log(sum/count);