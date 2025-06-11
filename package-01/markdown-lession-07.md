# 行内代码与代码块

## 一 : 行内代码

行内代码，顾名思义，就是某一行文字中，里面包括了一点代码

**语法** : `代码`

例如: 
    使用 `cd ..  ` 命令切换到上一级目录  
    使用 `mkdir 文件夹名字` 命令创建文件夹

## 二 : 代码块

**语法** :  

在一行里，一个TAB键 或 4个空格开头,就是一个代码块

下面是python代码

    def test_print():
        pass

下面是Java语言

    @Component
    class A{
        @Autowired
        private B b;

    }


    @Component
    class B{
        @Autowired
        private A a;

    }


## 三: 围栏代码块

**语法**:

```编程语言的名字
    
    编程内容。。。。
    
```


例如:

```python
def print_name():
    print("Markdown")
```

```sql
SELECT u.name, u.email, COUNT(o.id) as order_count
FROM users u
LEFT JOIN orders o ON u.id = o.user_id
WHERE u.created_at >= '2024-01-01'
GROUP BY u.id, u.name, u.email
ORDER BY order_count DESC
LIMIT 10;
```

```javascript
// 之前的代码
const oldFunction = () => {
    var x = 10;  // &#x274c; 使用 var
    console.log("Value: " + x);  // &#x274c; 字符串拼接
}

// 改进后的代码  
const newFunction = () => {
    const x = 10;  // &#x2705; 使用 const
    console.log(`Value: ${x}`);  // &#x2705; 模板字符串
}
```




