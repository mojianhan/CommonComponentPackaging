# CommonComponentPackaging

## url

>使用时候直接url('?id')

## 分页

```js
//使用时
//第一个参数是生成分页的盒子，第二个参数是当前页数，第三个参数是分页的size，最后一个是数据的总量
    pagingBuilder.build(pageBox, data.current_page, data.page_size, res.total_count);
    pagingBuilder.click(pageBox,function (page) {
        g.current_page = page;
        sortSearch(g);
    })
```