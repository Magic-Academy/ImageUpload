# ImageUpload
elementUI el-upload 二次封装组件

## 使用方式
例：
```
  <imageUpload :disabled="disabled" v-model="imgs" :isShowTip="false" :limit="1" />
 ```
  disabled为是否被禁用,默认为false  
  imgs为图片数据，可以传[String, Object, Array],上传返回v-model="imgs" ,上传之后imgs为String  
  limit为上传图片的数量  

---

disabled is whether it is disabled, the default is false  
imgs is image data, you can pass [String, Object, Array], upload returns v-model="imgs", after uploading imgs is String  
limit is the number of uploaded images  
