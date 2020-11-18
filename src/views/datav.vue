<template>
  <dv-full-screen-container>
    <dv-scroll-board :config="config" style="width: 100%; height: 100%" />
  </dv-full-screen-container>
</template>

<script>
// @ is an alias to /src

// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  data() {
    return {
      config: {
        header: ['<span style="font-size: 1.5em;">商品名称</span>', '<span style="font-size: 1.5em;">商品价格</span>', '<span style="font-size: 1.5em;">单位</span>'],
        rowNum: 10,
        carousel: "single",
        indexHeader: '<span style="font-size: 1.5em;">序号</span>',
        waitTime: 1000,
        data: [
          ["行1列1", "行1列2", "行1列3"],
          ["行2列1", "行2列2", "行2列3"],
          ["行3列1", "行3列2", "行3列3"],
          ["行4列1", "行4列2", "行4列3"],
          ["行5列1", "行5列2", "行5列3"],
          ["行6列1", "行6列2", "行6列3"],
          ["行7列1", "行7列2", "行7列3"],
          ["行8列1", "行8列2", "行8列3"],
          ["行9列1", "行9列2", "行9列3"],
          ["行10列1", "行10列2", "行10列3"],
          ["行11列1", "行11列2", "行11列3"],
          ["行12列1", "行12列2", "行12列3"],
        ],
        index: true,
        columnWidth: [100],
        align: ["center", "center", "center", "center"],
      },
    };
  },
};
</script>
<style>
.dv-scroll-board {
  color: #3c3f52;
  font-size: 2em;
}
.header {
  font-size: 2em;
}

.ceil {
  font-size: 1.5em;
}
</style>