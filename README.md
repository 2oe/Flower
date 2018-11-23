# Flower
花语

##### 项目介绍：
花语(Language of flowers)人们用花来表达人的语言，表达人的某种感情与愿望。花语虽无声，但此时无声胜有声。

##### 项目运行
    git@github.com:2oe/Flower.git
    npm install -D
    npm run start //开发环境
    npm run build // 线上环境

##### 项目接口:
    host: https://www.maoguzi.com
    
###### 首页接口

    @param page  页数
    @url get  /huayu/wp-json/wp/v2/posts?per_page=10&orderby=date&order=desc&page=${this.page}
    @return {
        data 数据,
        errMsg: 'request:ok',
        header: {},
        statusCode: 200
    }

###### 详情接口

    @param id  点击的id
    @url get  /huayu/wp-json/wp/v2/posts?per_page=10&orderby=date&order=desc&page=${id}
    @return {
        data 数据,
        errMsg: 'request:ok',
        header: {},
        statusCode: 200
    }
    
###### 搜索接口

    @param search  搜索的内容
    @url get  /huayu/wp-json/wp/v2/posts?per_page=10&orderby=date&order=desc&page=1&search=${search}
    @return {
        data 数据,
        errMsg: 'request:ok',
        header: {},
        statusCode: 200
    }
    
#####  项目截图

###### 首页

![image](https://note.youdao.com/yws/public/resource/6392f9a8eeaffcab4b29fdcd7c32db7a/xmlnote/2D21813D5B0B46F38D9FAEE134CF37E1/11353)

###### 详情

![image](https://note.youdao.com/yws/public/resource/6392f9a8eeaffcab4b29fdcd7c32db7a/xmlnote/0A58D2E114A64261B9BFCB257D325E71/11355)

###### 搜索

![image](https://note.youdao.com/yws/public/resource/6392f9a8eeaffcab4b29fdcd7c32db7a/xmlnote/5EAA0FDC3B7A49759C30D4C5B9EFBBD0/11357)