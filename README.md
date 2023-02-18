{
  "spider": "https://gh-proxy.com/https://raw.githubusercontent.com/FongMi/CatVodSpider/main/jar/custom_spider.jar;md5;e50bee173463b34db1d1faf3bbdffcaa",
  "wallpaper": "http://www.kf666888.cn/api/tvbox/img",
  "lives": [
    {
      "name": "直播",
      "type": 1,
      "url": "https://gh-proxy.com/https://raw.githubusercontent.com/FongMi/CatVodSpider/main/json/live.json",
      "epg": "http://epg.51zmt.top:8000/api/diyp/?ch={epg}&date={date}",
      "logo": "http://epg.51zmt.top:8000/{logo}"
    }
  ],
  "sites": [
    {
      "key": "哔哩",
      "name": "哔哩",
      "type": 3,
      "api": "csp_Bili",
      "searchable": 1,
      "filterable": 1,
      "changeable": 0,
      "ext": "https://gh-proxy.com/https://raw.githubusercontent.com/FongMi/CatVodSpider/main/json/bili.json"
    },
    {
      "key": "泥巴",
      "name": "泥巴",
      "type": 3,
      "api": "csp_NiNi",
      "searchable": 1,
      "filterable": 1,
      "changeable": 1
    },
    {
      "key": "獨播",
      "name": "獨播",
      "type": 3,
      "api": "csp_XPathMacFilter",
      "searchable": 1,
      "filterable": 1,
      "changeable": 1,
      "ext": "https://gh-proxy.com/https://raw.githubusercontent.com/FongMi/CatVodSpider/main/json/duboku.json"
    },
    {
      "key": "快播",
      "name": "快播",
      "type": 1,
      "api": "https://www.kuaibozy.com/api.php/provide/vod/",
      "searchable": 1,
      "filterable": 0,
      "changeable": 1,
      "categories": [
        "动漫",
        "国产剧",
        "日韩剧",
        "港台剧",
        "欧美剧",
        "泰剧",
        "动作片",
        "喜剧片",
        "爱情片",
        "科幻片",
        "恐怖片",
        "剧情片",
        "战争片",
        "纪录片",
        "综艺"
      ]
    },
    {
      "key": "百度",
      "name": "百度",
      "type": 1,
      "api": "https://api.apibdzy.com/api.php/provide/vod/",
      "searchable": 1,
      "filterable": 0,
      "changeable": 1,
      "categories": [
        "国产动漫",
        "日韩动漫",
        "大陆剧",
        "欧美剧",
        "韩剧",
        "日剧",
        "动作片",
        "喜剧片",
        "爱情片",
        "科幻片",
        "恐怖片",
        "剧情片",
        "战争片"
      ]
    },
    {
      "key": "櫻花",
      "name": "櫻花",
      "type": 3,
      "api": "csp_Ying",
      "searchable": 1,
      "filterable": 1,
      "changeable": 1
    },
    {
      "key": "巴士",
      "name": "巴士",
      "type": 3,
      "api": "csp_Dm84",
      "searchable": 1,
      "filterable": 1,
      "changeable": 1
    },
    {
      "key": "異界",
      "name": "異界",
      "type": 3,
      "api": "csp_Ysj",
      "searchable": 1,
      "filterable": 1,
      "changeable": 1
    },
    {
      "key": "紙條",
      "name": "紙條",
      "type": 3,
      "api": "csp_Paper",
      "searchable": 1,
      "filterable": 1,
      "changeable": 0,
      "ext": "https://agit.ai/Yoursmile7/TVBox/raw/branch/master/token.txt"
    },
    {
      "key": "易搜",
      "name": "易搜",
      "type": 3,
      "api": "csp_YiSo",
      "searchable": 1,
      "filterable": 0,
      "changeable": 0,
      "ext": "https://agit.ai/Yoursmile7/TVBox/raw/branch/master/token.txt"
    },
    {
      "key": "盤搜",
      "name": "盤搜",
      "type": 3,
      "api": "csp_PanSou",
      "searchable": 1,
      "filterable": 0,
      "changeable": 0,
      "ext": "https://agit.ai/Yoursmile7/TVBox/raw/branch/master/token.txt"
    },
    {
      "key": "UP雲搜",
      "name": "UP雲搜",
      "type": 3,
      "api": "csp_UpYun",
      "searchable": 1,
      "filterable": 0,
      "changeable": 0,
      "ext": "https://agit.ai/Yoursmile7/TVBox/raw/branch/master/token.txt"
    },
    {
      "key": "找資源",
      "name": "找資源",
      "type": 3,
      "api": "csp_Zhaozy",
      "searchable": 1,
      "filterable": 0,
      "changeable": 0,
      "ext": "https://agit.ai/Yoursmile7/TVBox/raw/branch/master/token.txt$$$yingshi$$$abcd1234"
    },
    {
      "key": "Live",
      "name": "直播",
      "type": 3,
      "api": "csp_Live",
      "searchable": 0,
      "filterable": 0,
      "changeable": 0,
      "ext": "2000"
    },
    {
      "key": "push_agent",
      "name": "推送",
      "type": 3,
      "api": "csp_Push",
      "searchable": 1,
      "filterable": 0,
      "changeable": 0,
      "ext": "https://agit.ai/Yoursmile7/TVBox/raw/branch/master/token.txt"
    }
  ]
}
