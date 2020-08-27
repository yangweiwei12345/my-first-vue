<template>
    <div>
        <div style="text-align: center; font-size: 32px;">{{msg}}</div>
        <div  style="text-align: center">{{moreMsg}}</div>
    </div>
</template>

<script lang="ts">
class Msg {
    public msg: string = 'hello world';
    GetMoreMsg(): string{
        return'webpack+vue+typescript+less'
    }
}
//创建msg对象
let MsgObj = new Msg();
export default {
    name: 'Hello',
    data() {
        return {
            msg: MsgObj.msg,
            moreMsg: MsgObj.GetMoreMsg()
        }
    },
}
</script>



