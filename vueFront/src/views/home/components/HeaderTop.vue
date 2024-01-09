<template>
    <div class="container">
        <div class="left left-header">
            <span>日期: </span>
            <span>
               {{time}}
            </span>
        </div>
        <div class="center">
            <div class="hometitle">回旋式空气预热器在线监测系统</div>
        </div>
        <div class="right right-header">
            <span>当前用户: </span>
            <span class="user-name">{{ userName }}</span>
        </div>
  </div>
</template>

<script>
export default {
    data() {
        return {
           time: "2024年1月1日",
           userName:"开发者"
        }
    },
}
</script>

<style lang="scss" scoped>
.header {
    text-align: center;
}

.hometitle {
    font-size: 21px;
    font-family: "Adobe Heiti Std";
    color: #70d2d4;
    line-height: 0.525;
    text-align: center;
}

.container {
    display: flex;
    justify-content: space-between;
    width: 100%;
    font-size: 24px;
    /* 调整字体大小 */
}

.left,
.center,
.right {
    border: 1px solid #000;
    /* 可选：添加边框样式 */
    padding: 10px;
    /* 可选：调整内边距 */
}
.left-header{
    font-size: 14px;
    font-family: "Adobe Heiti Std";
    color: white;
    line-height: 0.525;
    text-align: center;
}
.right-header {
    font-size: 14px;
    font-family: "Adobe Heiti Std";
    color: white;
    line-height: 0.525;
    text-align: center;
}
.user-name {
    margin-left: 5px;
}
</style>