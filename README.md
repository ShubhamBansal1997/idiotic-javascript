# Idiotic Javascript
Some of the absurd Javascript results, found during work

## Some With Strings And Number
```
>>"1" === 1
>>true
>>"1" + 1 === 1 + 1
>>false
```

## Some with Arrays
```
>>test = [1]
>>[ 1 ]
>>test == test
>>true
>>test == !test
>>true
```

## Some Not Defined things
```
>>typeof undefined
>>'undefined'
>>undefined==undefined
>>true
>>typeof NaN
>>'number'
>>NaN==NaN
>>false
>>typeof null
>>'object'
>>null==null
>>true
>>typeof {} + {}
>>[object Object][object Object]'
>>a = {} + {}
>>typeof a
>>'string'
```

## Some Math Fucks Up
```
>>Math.max()
>>-Infinity
>>Math.min()
>>Infinity
>>Math.max()==Math.max()
>>true
>>Math.min()==Math.min()
>>true
>>Math.min() + 1 == Math.min() + 1
>>true
>>Math.min() + 2 == Math.min() + 2
>>true
>>Math.max() + 1 == Math.max() + 1
>>true
>>Math.max() + 2 == Math.max() + 2
>>true
>>99999999999999999999
>>100000000000000000000
>>0.1+0.2
>>0.30000000000000004
```

## Some Array Knowledge Is Quite Imp
```
>>{} + []
>>0
>>[] + {}
>>'[object Object]'
>>{} + {}
>>'[object Object][object Object]'
>>[] + []
>>''
>>({} + {}).length
>>30
>>({}+[]).length
>>15
>>([]+[]).length
>>0
>>([]+![]).length
>>5
>>Array(3)==',,'
>>true
>>typeof ',,'
>>string
>>typeof Array(3)
>>'object'
>>Array()==false
>>true
```

## Some Boolean Things
```
>>true===1
>>false
>>true+true===2
>>true
```


