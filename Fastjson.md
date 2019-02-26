# Fastjson

### 注意fastjson 在把Object对象转成json字符串时会丢失字段
1. 实体类丢失属性原因：生成的get/set方法不规范
2. map丢失key原因：key对应的值为null，需要SerializerFeature序列化属性
