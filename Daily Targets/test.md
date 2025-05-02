# Battle #2 - Visibility

## #13 - Totally Triangle

[Link to the problem](https://cssbattle.dev/play/RWjRJZqaY8y1481oqgNg)

![result](https://firebasestorage.googleapis.com/v0/b/cssbattleapp.appspot.com/o/user%2Fummd3POvEDfFyeFvVdOMG3OOrwE2%2Ftargets%2Ftarget_xmSMJes.png?alt=media)

```html
  <div class='a'></div>
  <style>
    body{
      background: #EFF8FE;
      margin: 0;
    }
    .a {
      width: 60px;
      height: 300px;
      background: #4F77FF;
      margin: auto;
    }
    .a::before{
      content: '';
      display: block;
      height: 186px;
      width: 60px;
      background: #4F77FF;
      position: absolute;
      bottom: 0px;
      transform: translateX(-54px) rotateZ(-30deg);
      border-top-left-radius: 30px;
      border-top-right-radius: 30px;
    }
     .a::after{
      content: '';
      display: block;
      height: 186;
      width: 60;
      background: #4F77FF;
      position: absolute;
      bottom: 0px;
      transform: translateX(53px) rotateZ(30deg);
      border-top-left-radius: 30px;
      border-top-right-radius: 30px;
    }
  </style>
```
