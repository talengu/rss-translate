# rss-translate

rss translate any to any

![](https://github.com/talengu/rss-translate/workflows/circle_translate/badge.svg)
![](https://github.com/talengu/rss-translate/workflows/Deploy/badge.svg)

you can edit [test.ini](https://github.com/talengu/rss-translate/edit/main/test.ini) to add orginal rss url. [help](https://github.com/talengu/rss-translate/issues/2)

next find the translated link in [https://talengu.github.io/rss-translate/](https://talengu.github.io/rss-translate/)

## 20230814 update
- support proxy mode. you can set `action = "proxy"` in test.ini like [source010](https://github.com/talengu/rss-translate/blob/f6648c5262f4fa0926310dbe43fff820bf727ac7/test.ini#L67)

## 20230702 update 
- use [main2.py](https://github.com/talengu/rss-translate/blob/main/main2.py) in [circle_translate.yml](https://github.com/talengu/rss-translate/blob/aeb61bc36eb1a22fd003677b5209291cf7cb4a87/.github/workflows/circle_translate.yml#L38)
- atom is bad now base on an atom paraser to find. NOW SUPPORT
        use [feedparser](https://pythonhosted.org/feedparser/)
- fix google translate limit . NOW SUPPORT

## rss translate links

 - source001 [http://www.mckinsey.com/insights/rss](http://www.mckinsey.com/insights/rss) -> [mckinsey_rss.xml](rss/mckinsey_rss.xml)
 - source002 [http://www.mckinsey.com/insights/rss](http://www.mckinsey.com/insights/rss) -> [mckinsey_iw_rss.xml](rss/mckinsey_iw_rss.xml)
 - source003 [http://rss.acast.com/nature](http://rss.acast.com/nature) -> [nature_rss.xml](rss/nature_rss.xml)
 - source004 [https://rss-bridge.org/bridge01/?action=display&bridge=ReutersBridge&feed=home/topnews&format=Atom](https://rss-bridge.org/bridge01/?action=display&bridge=ReutersBridge&feed=home/topnews&format=Atom) -> [Reuters_rss.xml](rss/Reuters_rss.xml)
 - source005 [https://rss-bridge.org/bridge01/?action=display&bridge=ReutersBridge&feed=china&format=Atom](https://rss-bridge.org/bridge01/?action=display&bridge=ReutersBridge&feed=china&format=Atom) -> [Reuters china_rss.xml](rss/Reuters%20china_rss.xml)
 - source006 [https://www.profgalloway.com/feed/](https://www.profgalloway.com/feed/) -> [No Mercy No Malice_rss.xml](rss/No%20Mercy%20No%20Malice_rss.xml)
 - source007 [https://rss-bridge.org/bridge01/?action=display&bridge=ReutersBridge&feed=home/topnews&format=Atom](https://rss-bridge.org/bridge01/?action=display&bridge=ReutersBridge&feed=home/topnews&format=Atom) -> [economist latest_rss.xml](rss/economist%20latest_rss.xml)
 - source008 [https://rss-bridge.org/bridge01/?action=display&bridge=EconomistWorldInBriefBridge&limit=100&agenda=on&agendaPictures=on&format=Atom](https://rss-bridge.org/bridge01/?action=display&bridge=EconomistWorldInBriefBridge&limit=100&agenda=on&agendaPictures=on&format=Atom) -> [economist this week_rss.xml](rss/economist%20this%20week_rss.xml)
 - source009 [https://www.kali.org/rss.xml](https://www.kali.org/rss.xml) -> [kali.xml](rss/kali.xml)
 - source010 [https://www.v2ex.com/index.xml](https://www.v2ex.com/index.xml) -> [v2ex.xml](rss/v2ex.xml)
