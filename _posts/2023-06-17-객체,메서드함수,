# 객체와 메서드함수 및 this

> const 객체  ={
> property:value,
> property:value }
> 
*(예)*

    const  rabbit  ={
              name : 'bunny',
              color : 'white',
              hop: function() {
              console.log(`${this.name} can hopitti hop!`) }
    };

    rabbit.hop(); 
    //bunny can hopitti hop!
    

rabbit이라는 객체에 대해서 설명해주고 있고 
안에 function도 넣어서 할수 있는 동작 또한 포함시킬 수 있다. 이때 this 키워드를 사용해보았다.

    const rabbit2= rabbit.hop;

하지만 변수 안에 객체 rabbit의 hop 함수 메서드를 저장하고 사용하려고 한다면,  
undefined can hopitti hop! 이 나오는데
이는 rabbit 객체 리터럴에 접근하지 않고 
window.hop이라고 사용하기 때문이다. 






