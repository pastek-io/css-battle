# Daily Targets: 23 September 2024

[Target (23/9/2024) - CSSBattle](https://cssbattle.dev/play/GoiTWX55zI8T9xtWnj84)

![23 September 2024](./result.png)

``` html
<div></div>
<style>
  body {
    background: #5D3A3A;
    display: grid;
    place-items: center;
  }
  div {
    width: 200px;
    height: 40px;
    background: #B5E0BA;
    position: relative;
  }
  div::before {
    content: '';
    width: 60px;
    height: 60px;
    position: absolute;
    top: -200%;
    left: 50%;
    transform: translateX(-50%);

    border-radius: 50px;
    background: #B5E0BA;
  }
  div::after {
    content: '';
    width: 60px;
    height: 60px;
    position: absolute;
    top: 150%;
    left: 50%;
    transform: translateX(-50%);

    border-radius: 50px;
    background: #B5E0BA;
  }
</style>
```