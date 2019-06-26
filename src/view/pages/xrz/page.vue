<template>
    <div>
        <div class="card">
            <div class="title">本月入职</div>
            <div class="content">15</div>
        </div>

        <div class="card" style="float:left;position:absolute;left:50%;margin-left:-50px;">
            <div class="title">上月月入职</div>
            <div class="content">10</div>
        </div>

        <div style="clear:both;"></div>

        <div style="padding:20px;border:1px solid;">test</div>
    </div>
</template>

<style scoped>
    .card{
        margin:40px 20px;
        height:100px;
        width: 100px;
        border-radius: 10px;
        border: 1px solid #eeeeee;
        background-color: #fff;
        float:left;
    }

    .title{
        height:40px;
        line-height: 40px;
        text-align: center;
        border-bottom: 1px solid #ccc;
        font-weight: bold;
    }

    .content{
        text-align: center;
        line-height: 60px;
        font-weight: bolder;
        font-size: 1.5rem;
    }
</style>
