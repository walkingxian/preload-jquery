# preload-jquery
jquery预加载图片插件
# 使用方法
$.preload(imgs,function() {
  order:'ordered',  //预加载方式（有序或无序）
  each:function(count){
    //每个图片加载完成后调用
  },
  all:function(){
    //所以图片加载完成后调用
  }
})
