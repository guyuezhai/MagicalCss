# MagicalCss
some wonderfull css case

* 走马灯效果
* canvas 时钟
  
```
     <style>
        .riding{
            height: 25px;
            line-height: 25px;
            border: 1px red dashed;
            overflow: hidden;
            word-break: break-all;
            white-space: nowrap;
        }
        .riding_text{
            display: inline-block;
            padding-left: 100%;
            animation: riding 16s linear infinite;
        }
        @keyframes riding{
            0% {transform: translate(0,0);}
            100% {transform: translate(-100%,0);}
        }
    </style>

    <div class="riding">
        <span class="riding_text">
            欢迎前来观看走马灯效果！
        </span>
    </div>
```

![canvas 时钟](https://github.com/guyuezhai/MagicalCss/image/clock.jpg "canvas 时钟")