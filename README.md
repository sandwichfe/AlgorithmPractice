### use practice algorithm


模版配置：  

**codeFileName：**
```java
$!velocityTool.camelCaseName(${question.titleSlug})
```


**Code Template：**
```java
${question.content}
package leetcode.editor.cn;
/**
 * ${question.title}
 * @author lww
 * @since $!velocityTool.date()
 */
public class $!velocityTool.camelCaseName(${question.titleSlug}) {
public static void main(String[] args) {
    Solution solution = new $!velocityTool.camelCaseName(${question.titleSlug})().new Solution();
}
/**
 * Solution
 */
${question.code}
}
```