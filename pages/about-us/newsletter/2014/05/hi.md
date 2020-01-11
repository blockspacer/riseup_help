@title = 'मई 2014 की विषयसूची'


## हमारा सुरक्षा संबंधी बयान

यदि आप राज्‍य के निगरानी तंत्र के साथ Riseup के संपर्क या पत्र-व्‍यवहार के बारे में अपडेट प्राप्‍त करना चाहते हैं, तो इस लिंक को चेक करें: 
https://help.riseup.net/hi/canary

हम लगभग हर तीन महीने पर इसे अपडेट करते रहेंगे।

फिलहाल इसमें लिखा गया है:
 
21 अप्रैल, 2014 तक Riseup को कोई नेशनल सिक्‍योरिटी लेटर या FISA कोर्ट ऑर्डर नहीं मिला है, और फिलहाल हमें FISA कोर्ट के माध्‍यम किसी प्रतिबंध आदेश का शिकार नहीं बनाया गया है। Riseup ने कभी अपने सॉफ्टवेयर में कोई बैक-डोर सॉफ्टवेयर नहीं लगाया है और ना ही ऐसा करने का कोई अनुरोध हमें मिला है। Riseup ने कभी किसी तीसरे पक्ष को किसी भी उपयोगकर्ता के संदेश नहीं सौंपे और ना ही उजागर किए हैं। 

एक व्‍यापक प्रचारित घटना में, सर्वर जब्‍त करने के संबंध में हम बताना चाहते हैं कि एफबीआई ने अप्रैल 2012 में Riseup का एक सर्वर जब्‍त किया था। यह घटना न्‍यूयॉर्क की है। वह मशीन एन्क्रिप्‍ट की हुई थी और उसमें उपयोगकर्ताओं संबंधी कोई डेटा नहीं था। वह सर्वर हमें लौटा दिया गया था लेकिन हमने दोबारा उसका इस्‍तेमाल नहीं किया। Riseup पुष्टि करता है कि इस घटना के सिवाय,  21 अप्रैल 2014 तक इसका कोई हार्डवेयर किसी तीसरे पक्ष ने जब्‍त नहीं किया, न ही कोई इसे ले गया।


## याहू और मेलिंग लिस्‍ट

yahoo.com और aol.com पर भेजी गयीं आपकी मेल वापस लौट रही होंगी। इसका कारण इन कॉरपोरेशन की नीति में किए गए बदलाव हैं। उन्‍होंने DMARC रिकॉर्ड (एक एंटी-स्‍पैम तकनोलॉजी) प्रकाशित किया था जो कहता है कि ''यदि हमारे आधिकारिक सर्वरों के अतिरिक्‍त कोई भी सर्वर किसी प्रेषक की मेल yahoo.com (या aol.com) के पते का इस्‍तेमाल करके भेजता है, तो उसे स्‍पैम माना जाएगा और अस्‍वीकृत कर दिया जाएगा।'' DMARC रिकॉर्ड इसके बाद से कोई मेल मिलने पर क्‍या करना इसका निर्णय करने के लिए अन्‍य साइटों द्वारा भी इस्‍तेमाल किया जाता है (जैसे हॉटमेल डॉट कॉम, कॉमकास्‍ट डॉट नेट, और अन्‍य बहुत-सी कंपनियां)।

इसमें समस्‍या यह है कि, lists.riseup.net जैसे मेलिंग लिस्‍ट सॉफ्टवेयर संदेशों को अन्‍य ईमेल पतों पर दोबारा भेजते हैं। इसलिए जब याहू या एओएल के उपयोगकर्ता लिस्‍ट पर संदेश भेजते हैं और वह संदेश पुनर्वितरित होता है, तो प्राप्‍तकर्ता मेल सर्वर बताता है कि ''यह संदेश किसी याहू/एओएल सर्वर से नहीं भेजा गया था, यह स्‍पैम हो सकता है, इसे अस्‍वीकृत करें!'' और संदेश को वापस भेज देता है यानी बाउंस कर देता है। इसीलिएआपको केवल याहू या एओएल ही नहीं बल्कि अन्‍य साइटों से भी ढेरों बाउंस संदेश मिल रहे होंगे।j  

इसके बारे में विस्‍तार से यहां पढ़ सकते हैं: http://jrl.guru/Email/yahoobomb.html

इसे ठीक करने का सबसे आसान तरीका यह है कि याहू/एओएल अपनी नीति में बदलाव करें।
लेकिन तब तक riseup यह उपाय कर रहा है:

* नुकसान को सीमित करने के लिए, अब हम को lists.riseup.net पर मेल भेजने के लिए yahoo.com या aol.com के पतों का इस्‍तेमाल करने वाले सभी प्रेषकों को ब्‍लॉक कर रहे हैं।
संदेश भेजने पर yahoo.com और aol.com प्रेषकों को तुरंत त्रुटि संदेश मिल जाएगा जिसमें चीजों को स्‍पष्‍ट किया गया होगा। यह प्रेषकों के लिए खराब है, लेकिन इससे बड़े पैमाने पर बाउंस और बाउंस संबंधी अनसब्‍सक्रिप्‍शन रुक जाएंगे।
* हम हरेक को प्रोत्‍साहित करते हैं कि वे याहू/एओएल के बजाय ऐसे ईमेल प्रदाता का इस्‍तेमाल करें जो आपकी निजता की रक्षा करता हो और मेलिंग लिस्‍टों के संचालन असंभव नहीं बनाता हो।
* हम इस समस्‍या के समाधान के अन्‍य तरीकों की पड़ताल कर रहे हैं, और उम्‍मीद है जल्‍द ही इससे निपटने का कोई तरीका निकल आएगा।


## पैसा!

आपको पैसे की तंगी है? हमें भी है। यदि आप मामूली रकम भी Riseup को सहयोग के रूप में दे सकें तो, प्रत्‍येक छोटी राशी पूरी दुनिया के हजारों समूहों और एक्टिविस्‍टों को सहायता पहुंचाती है। 
https://help.riseup.net/hi/donate

और जिन माध्‍यमों से लोग Riseup को आर्थिक सहयोग करते हैं उनमें से एक, wepay, ने अनुदान स्‍वीकार करना बंद कर दिया है। जिस किसी ने उनके जरिए आवर्ती अनुदान निर्धारित किया था, वे यदि किसी और तरीके से आवर्ती यानी बारंबार भुगतान सुनिश्चित कर सकें तो बहुत अच्‍छा रहेगा। धन्‍यवाद!