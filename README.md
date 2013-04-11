 
/* 
   Name: 中国全部城市的json数据：
	 Description:    可以自己添加数据：格式：  中文名|全拼|简拼
	 Author: markyun
	 Email：MyGood@126.com  
	 Author URL: http://weibo.com/920802999
	 Version: 1.0
	 UpdateTime:2013-4-10
*/ 
.ChinaCity =   ['北京|beijing|bj','上海|shanghai|sh', '重庆|chongqing|cq',  '深圳|shenzhen|sz', '广州|guangzhou|gz', '杭州|hangzhou|hz',
    '南京|nanjing|nj', '苏州|shuzhou|sz', '天津|tianjin|tj', '成都|chengdu|cd', '南昌|nanchang|nc', '三亚|sanya|sy','青岛|qingdao|qd',
    '厦门|xiamen|xm', '西安|xian|xa','长沙|changsha|cs','合肥|hefei|hf', '安庆|anqing|aq', '安康|ankang|ak',
    '阿克苏|akesu|aks', '包头|baotou|bt', '北海|beihai|bh', '百色|baise|bs','保山|baoshan|bs', '长治|changzhi|cz', '长春|changchun|cc', '常州|changzhou|cz',
    '朝阳|chaoyang|cy', '常德|changde|cd','赤峰|chifeng|cf', '大同|datong|dt', '大连|dalian|dl', '达州|dazhou|dz', '东营|dongying|dy', '大庆|daqing|dq', '丹东|dandong|dd',
    '大理|dali|dl', '敦煌|dunhuang|dh',  '恩施|enshi|es', '鄂尔多斯|eerduosi|eeds','福州|fuzhou|fz', '阜阳|fuyang|fy', '贵阳|guiyang|gy',
    '桂林|guilin|gl', '广元|guangyuan|gy', '哈密|hami|hm','呼和浩特|huhehaote|hhht', 
    '黑河|heihe|hh', '哈尔滨|haerbin|heb', '海口|haikou|hk', '黄山|huangshan|hs', '邯郸|handan|hd',
    '汉中|hanzhong|hz', '和田|hetian|ht', '晋江|jinjiang|jj', '锦州|jinzhou|jz', '景德镇|jingdezhen|jdz',
    '嘉峪关|jiayuguan|jyg','济宁|jining|jn', '九江|jiujiang|jj', '佳木斯|jiamusi|jms', '济南|jinan|jn',
    '喀什|kashi|ks', '昆明|kunming|km','克拉玛依|kelamayi|klmy',  '兰州|lanzhou|lz',
    '洛阳|luoyang|ly', '丽江|lijiang|lj', '柳州|liuzhou|lz', '泸州|luzhou|lz', '连云港|lianyungang|lyg',
　'临沧|lincang|lc', '临沂|linyi|ly','绵阳|mianyang|my','牡丹江|mudanjiang|mdj', 
   '南充|nanchong|nc', '南宁|nanning|nn', '南阳|nanyang|ny', '南通|nantong|nt', 
    '宁波|ningbo|nb', '攀枝花|panzhihua|pzh', '衢州|quzhou|qz', '秦皇岛|qinhuangdao|qhd', '齐齐哈尔|qiqihaer|qqhe','庆阳|qingyang|qy', 
    '石家庄|shijiazhuang|sjz',  '沈阳|shenyang|sy','铜仁|tongren|tr', '台州|taizhou|tz',
    '太原|taiyuan|ty', '威海|weihai|wh','文山|wenshan|ws', '无锡|wuxi|wx', '潍坊|weifang|wf',
    '温州|wenzhou|wz', '乌鲁木齐|wulumuqi|wlmq',    '西宁|xining|xn',  '西双版纳|xishuangbanna|xsbn', '徐州|xuzhou|xz',  '永州|yongzhou|yz', '榆林|yulin|yl', '延安|yanan|ya', '运城|yuncheng|yc', '烟台|yantai|yt', '银川|yinchuan|yc', '宜昌|yichang|yc', '宜宾|yibin|yb', '盐城|yancheng|yc', '珠海|zhuhai|zh', '昭通|zhaotong|zt',
'张家界|zhangjiajie|zjj', '舟山|zhoushan|zs', '郑州|zhengzhou|zz', '安顺|anshun|as', '安阳|anyang|ay', '鞍山|anshan|as', '巴中|bazhong|bz', '白城|baicheng|bc', '白山|baishan|bs', '白银|baiyin|by', '蚌埠|bengbu|bb', '宝鸡|baoji|bj', '保定|baoding|bd', '本溪|benxi|bx', '毕节|bijie|bj', '滨州|binzhou|bz', '毫州|haozhou|hz', '沧州|cangzhou|cz', '潮州|chaozhou|cz', '郴州|chenzhou|cz', '承德|chengde|cd', '池州|chizhou|cz', '崇左|chongzuo|cz', '滁州|chuzhou|cz', '楚雄|chuxiong|cz', '达州|dazhou|dz', '德宏|dehong|dh', '德阳|deyang|dy', '德州|dezhou|dz', '定西|dingxi|dx', '东莞|dongguan|dg', '鄂州|ezhou|ez', '防城港|fangchenggang|fcg', '佛山|foshan|fs', '抚顺|fushun|fs', '抚州|fuzhou|fz', '阜新|fuxin|fx', '赣州|ganzhou|gz', '固原|guyuan|gy', '广安|guangan|ga', '贵港|guigang|gg', '河池|hechi|hc', '河源|heyuan|hy', '菏泽|heze|hz', '贺州|hezhou|hz', '鹤壁|hebi|hb', '鹤岗|hegang|hg', '衡水|hengshui|hs', '衡阳|hengyang|hy', '红河|honghe|hh', '湖州|huzhou|hz', '葫芦岛|huludao|hld', '怀化|huaihua|hh', '淮安|huaian|ha', '淮北|huaibei|hb', '淮南|huainan|hn', '黄冈|huanggang|hg', '黄山|huangshan|hs', '黄石|huangshi|hs', '惠州|huizhou|hz', '鸡西|jixi|jx', '吉安|jian|ja', '吉林|jilin|jl', '嘉兴|jiaxing|jx', '江门|jiangmen|jm', '焦作|jiaozuo|jz', '揭阳|jieyang|jy', '金昌|jinchang|jc', '金华|jinhua|jh', '晋城|jincheng|jc', '晋中|jinzhong|jz', '荆门|jingmen|jm', '荆州|jingzhou|jz', '酒泉|jiuquan|jq', '开封|kaifeng|kf', '来宾|laibin|lb', '莱芜|laiwu|lw', '廊坊|langfang|lf', '乐山|leshan|ls', '丽水|lishui|ls', '凉山|liangshan|ls', '辽阳|liaoyang|ly', '聊城|liaocheng|lc', '临汾|linfen|lf', '六安|luan|bz', '六盘水|liupanshui|lps', '龙岩|longyan|ly', '陇南|longnan|ln', '娄底|loudi|ld', '吕梁|lvliang|ll', '漯河|luohe|lh', '马鞍山|maanshan|mas', '茂名|maoming|mm', '眉山|meishan|ms', '梅州|meizhou|mz', '内江|neijiang|nj', '南平|nanping|np', '宁德|ningde|nd', '盘锦|panjin|pj', '平顶山|pingdingshan|pds', '平凉|pingliang|pl', '萍乡|pingxiang|px', '莆田|putian|pt', '濮阳|puyang|py', '普洱|puer|pr', '七台河|qitaihe|qth', '黔东南|qiandongnan|qdn', '黔南|qiannan|qn', '黔西南|qianxinan|qxn', '钦州|qinzhou|qz', '清远|qingyuan|qy', '曲靖|qujing|qj', '泉州|quanzhou|qz', '日照|rizhao|rz', '三门峡|sanmenxia|smx', '三明|sanming|sm', '陵水|lingshui|ls', '汕头|shantou|st', '汕尾|shanwei|sw', '商洛|shangluo|sl', '商丘|shangqiu|sq', '濮阳|puyang|py', '上饶|shangrao|sr', '韶关|shaoguan|sg', '邵阳|shaoyang|sy', '绍兴|shaoxing|sx', '深圳|shenzhen|sz', '十堰|shiyan|sy', '石嘴山|shizuishan|szs', '双鸭山|shuangyashan|sys', '朔州|shuozhou|sz', '四平|siping|sp', '松原|songyuan|sy', '宿迁|suqian|sq', '宿州|suzhou|sz', '绥化|suihua|sh', '随州|suizhou|sz', '遂宁|suining|sn', '濮阳|puyang|py', '泰安|taian|ta', '泰州|taizhou|tz', '唐山|tangshan|ts', '天水|tianshui|ts', '铁岭|tieling|tl', '通化|tonghua|th', '铜川|tongchuan|tc', '铜陵|tongling|tl', '吐鲁番|tulufan|tlf', '威武|weiwu|ww', '渭南|weinan|wn', '吴忠|wuzhong|wz', '芜湖|wuhu|wh', '武汉|wuhan|wh', '仙桃|xiantao|xt', '咸宁|xianning|xn', '咸阳|xianyang|xy', '湘潭|xiangtan|xt', '湘西|xiangxi|xx', '襄阳|xiangyang|xy', '孝感|xiaogan|xg', '忻州|xinzhou|xz', '新乡|xinxiang|xx', '新余|xinyu|xy', '信阳|xinyang|xy', '邢台|xingtai|xt', '许昌|xuchang|xc', '宣城|xuancheng|xc', '雅安|yaan|ya', '延边|yanbian|yb', '扬州|yangzhou|yz', '阳江|yangjiang|yj', '阳泉|yangquan|yq', '伊春|yichun|yc', '宜春|yichun|yc', '益阳|yiyang|yy', '鹰潭|yingtan|yt', '营口|yingkou|yk', '玉林|yulin|yl', '玉溪|yuxi|yx', '岳阳|yueyang|yy', '云浮|yunfu|yf', '枣庄|zaozhuang|zz', '张家口|zhangjiakou|zjk', '张掖|zhangye|zy', '漳州|zhangzhou|zz', '肇庆|zhaoqing|zq', '镇江|zhenjiang|zj', '中山|zhongshan|zs', '周口|zhoukou|zk', '株洲|zhuzhou|zz', '驻马店|zhumadian|zmd', '资阳|ziyang|zy', '临淄|linzi|lz', '自贡|zigong|zg', '遵义|zunyi|zy'];
