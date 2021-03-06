# योगदान करना

यदि आप योगदान करने में इच्छुक हैं, तो कृपया पहले [आचार संहिता](./CODE_OF_CONDUCT.md) देखें।

## अनुवाद

अनुवाद **३** भागों के रूप में मौजूद हैं, जिन्हें आप अपनी इच्छानुसार एकल पुल-अनुरोध के रूप में प्रस्तुत कर सकते हैं।

### साइट प्रलेखन

साइट प्रलेखन फाइलें `./github/lang` निर्देशिका के अंतर्गत मौजूद हैं। यदि आप अनुवाद प्रस्तुत करना चाहते हैं, तो कृपया [अपनी भाषा के लिए दो-अक्षर का आईएसओ-कोड](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) के अनुसार निम्नलिखित फाइलें प्रदान करें।

जैसे चीनी

* `.github/lang/README.zh.md`
* `.github/lang/CONTRIBUTING.zh.md`

अपने नए `README.zh.md` और `CONTRIBUTING.zh.md` फ़ाइलों के बीच लिंक को अपडेट करें ताकि `README.zh.md` के अंदर ***योगदान*** लिंक पर क्लिक करने से  सीधे `CONTRUTUTING.zh.md` पर चले जाएं।

### i18n

भाषा की फाइलें `lang/` के अंतर्गत रहती हैं और एक जावास्क्रिप्ट फ़ाइल के रूप में मौजूद होती हैं, जिसका नाम आपकी भाषा के लिए [दो-अक्षर का आईएसओ-कोड](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) के अनुसार होता है।

जैसे हिंदी

* `lang/hi.js`

आपको अपनी नई भाषा फ़ाइल में `lang/en.js` को कॉपी करना चाहिए, फिर हर स्ट्रिंग का अनुवाद करने के लिए आगे बढ़ना चाहिए। ऐसे किसी भी स्ट्रिंग को न तोड़े जो मार्कअप में शामिल हैं।

### सामग्री

सामग्री `content/` निर्देशिका में एक निर्देशिका के तहत रहती है, जिसका नाम आपकी भाषा के लिए [दो-अक्षर का आईएसओ-कोड](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) के अनुसार होता है।

जैसे स्पेनिश (मुख्य भूमि)

* `content/es/`

आपको अपनी नई भाषा निर्देशिका में `content/en/` निर्देशिका को कॉपी करना चाहिए, फिर उन फ़ाइलों की सभी सामग्री का अनुवाद करने के लिए आगे बढ़ना चाहिए। मौजूद किसी भी एचटीएमएल में छेड़छाड़ न करे। दस्तावेजों के शीर्ष पर फ्रंटमैटर का वर्तमान में उपयोग नहीं किया गया है, लेकिन कृपया उसका भी अनुवाद करें।

वर्तमान में अनुवादित की जाने वाली फाइलें यह हैं:

* `details.md`
* `index.md`

## समस्याएं

किसी समस्या के लिए अधिक जानकारी चाहिए हो तो कृपया संदेश भेजें, और उसे अपना मानें। तब आप इस पर काम कर सकते हैं, और एक बार तैयार होने के बाद पीआर भेज सकते हैं।

पुल-अनुरोध भेजने के लिए, कृपया सुनिश्चित करें कि आप रिपॉज़िटरी को फोर्क कर रहे हैं इससे पहले कि आप इसे बंद कर दें। कृपया इस `main` ब्रांच के लिए एक पुल-अनुरोध बनाने से पहले अपनी `main` ब्रांच को संशोधित न करें। संदेह होने पर कृपया पूछें।

## अन्य सुधार

कृपया अप्रत्याशित पुल-अनुरोध न भेजें। कृपया कुछ भी काम करने से पहले एक नया मुद्दा बनाइये।
