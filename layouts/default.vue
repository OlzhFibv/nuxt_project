<template>
  <div>
    <Nuxt />
  </div>
</template>

<style>
html {
  font-family:
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #135cf8;
  color: #ffffff;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #4340ff;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #0099ff;
  color: #ffffff;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #0077ff;
}
.button--geron {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #e1f813;
  color: #fff2f2;
  text-decoration: none;
  padding: 20px 40px;
}

.button--geron:hover {
  color: rgb(0, 0, 0);
  background-color: #fffb06;
}
</style>
