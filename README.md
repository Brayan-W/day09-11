# day09-11
a website

### 为图片添加遮罩层
```
  #crew .tutors-album .tutors {
      margin-top: 50px;
      position: relative;
  }

  #crew .tutors-album .tutors .mask{
      /* hover蒙版 */
      position: absolute;
      /* 用flex来使其垂直水平居中 */
      display: flex;
      justify-content:center;
      align-items: center;
      flex-direction: column;
      color: white;
      background-color: rgba(20, 20, 20, 0.65);
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      opacity: 0;
  }
  #crew .tutors-album .tutors .mask .links a{
      color: inherit;
      text-decoration: none;
  }

  #crew .tutors-album .tutors .mask .links .iconfont{
      font-size: 50px !important;
      margin: 15px;
  }
  #crew .tutors-album .tutors .mask p:nth-child(1){
      font-size: 26px;
      padding-bottom: 10px;
  }
  #crew .tutors-album .tutors .mask p:nth-child(2){
      color: rgba(158, 158, 158, 0.7);
      margin-bottom: 30px;
  }
  #crew .tutors-album .tutors:hover .mask{
      opacity: 1;
  }
```
 ### 从iconfont上引用一些图标
 ### flex弹性盒子
