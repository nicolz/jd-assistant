# JD-Assistant

[![version](https://img.shields.io/badge/python-3.4+-blue.svg)](https://www.python.org/download/releases/3.4.0/) 
[![status](https://img.shields.io/badge/status-stable-green.svg)](https://github.com/whyour/jd-assistant)
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)
[![star, issue](https://img.shields.io/badge/star%2C%20issue-welcome-brightgreen.svg)](https://github.com/whyour/jd-assistant)

京东抢购助手

本仓库`fork`自[tychxn](https://github.com/tychxn/jd-assistant)

## 新增功能
- 登陆京东商城（[www.jd.com](http://www.jd.com/)）
  - linux默认terminal显示二维码

## 运行环境

- [Python 3](https://www.python.org/)

## 第三方库

- [qrcode](https://github.com/lincolnloop/python-qrcode)
- [zxing](https://github.com/dlenski/python-zxing)
- [Requests](http://docs.python-requests.org/en/master/)
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [PyCryptodome](https://github.com/Legrandin/pycryptodome)

## 安装
```sh
python3 -m pip install -r requirements.txt
```

## 使用教程

运行程序 `python3 main.py`

## 更新记录

## 备注

- 有指纹、人脸识别的需要关闭，这样才可使用红包京豆等虚拟财产时，使用支付密码。
- 🌟强烈建议大家在部署代码前使用有货的商品测试下单流程，并且：在京东购物车结算页面设置发票为`电子普通发票-个人`，设置支付方式为`在线支付`，否则可能出现各种未知的下单失败问题。🌟
  
## 待完成的功能

- [ ] Keep session alive
