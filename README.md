# Química³ 

<style>
.container{
  display: flex;
  align-items: center;
  justify-content: center;
    padding-top: 20px;
    padding-bottom: 40px;
}

.atom {
  position: relative;
  width: 100px;
  height: 100px;
   border-style: solid;
  border-color: #f3f3f3;
  border-radius: 50%;
  animation: rotate 3s linear infinite;
}

.nucleus {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 30px;
  height: 30px;
  background-color:  #6d00a1; 
  border-radius: 50%;
}

.electron {
  position: absolute;
  top: 0;
  left: 50%;
  transform: translateX(-50%);
  width: 10px;
  height: 10px;
  background-color: #5086c1;
  border-radius: 50%;
  animation: orbit 3s linear infinite;
}

@keyframes rotate {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

@keyframes orbit {
  0% {
    transform: translateY(-50%) rotate(0deg);
  }
  100% {
    transform: translateY(-50%) rotate(360deg);
  }
}
</style>
<div class="container">
    <div class="atom">
        <div class="nucleus"></div>
        <div class="electron"></div>
    </div>
</div>

![GitHub last commit (branch)](https://img.shields.io/github/last-commit/AndreLuizdeLima/quimicaaocubo/main)
![GitHub issues](https://img.shields.io/github/issues/AndreLuizdeLima/quimicaaocubo)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/AndreLuizdeLima/quimicaaocubo)
![GitHub commit activity](https://img.shields.io/github/commit-activity/t/AndreLuizdeLima/quimicaaocubo?color=FF6347)

## Sobre
