## गलतियाँ करना

कभी-कभी गलती हो जाती है, तो चलिए आपके प्रोजेक्ट में 'साफ़ करें' बटन और इरेज़र जोड़ें!



+ चलिए स्टेज को क्लियर करने के लिए बटन जोड़ें। ऐसा करने के लिए, स्टेज में 'X-block' वर्ण स्प्राइट जोड़ें, और इसमें लाल रंग करें।

	![screenshot](images/paint-x.png)

+ अपने नए cancel बटन में कोड जोड़ें ताकि जब इस पर क्लिक किया जाता है तो स्टेज क्लियर हो जाए।

	```blocks
		इस स्प्राईट को क्लिक करने पर
		मिटा दे
	```

	ध्यान दें कि आपको स्टेज को क्लियर करने के लिए संदेश नहीं भेजना होगा, क्योंकि कोई भी स्प्राइट ऐसा कर सकती है!

+ शायद आपने ध्यान दिया होगा कि आपकी पेंसिल स्प्राइट में इरेज़र पोशाक शामिल है:

	![screenshot](images/paint-eraser-costume.png)
	

+ आपके प्रोजेक्ट में इरेज़र सिलेक्टर स्प्राइट भी शामिल होती है, इस पर राइट क्लिक करें और 'दिखाएँ' चुनें। आपकी स्टेज कुछ इस प्रकार दिखाई देगी:

	![screenshot](images/paint-eraser-stage.png)

+ इसके बाद आप पेंसिल को इरेज़र पर स्विच करने के लिए, इरेज़र सिलेक्टर स्प्राइट में कोड जोड़ सकते हैं।

	```blocks
		इस स्प्राईट को क्लिक करने पर
		[eraser v] प्रसारण करें
	```

+ जब पेंसिल को यह संदेश प्राप्त होता है, तो आप पेंसिल पोशाक को इरेज़र पर स्विच करके, और पेंसिल के रंग को स्टेज के रंग के रूप में बदल कर इरेज़र बना सकते हैं!

	```blocks
		मुझे [eraser v] मिलने पर
    पोशाक बदल कर [eraser v] करें
    पेन का रंग [#FFFFFF] पर सेट करे
	```

+ यह देखने के लिए अपने प्रोजेक्ट का परीक्षण करें कि क्या आप स्टेज पर क्लियर कर सकते हैं और मिटा सकते हैं।

	![screenshot](images/paint-erase-test.png)

+ पेंसिल में एक अन्य समस्या है – आप सिलेक्टर आइकन्स सहित, कहीं भी चित्र बना सकते हैं!

	![screenshot](images/paint-draw-problem.png)

	इसे ठीक करने के लिए, आपको पेंसिल को बताना होगा कि केवल तभी चित्र बनाए जब माउस पर क्लिक किया जाए _और_ यदि माउस की y-स्थिति -120 से अधिक हो (`माउस y` कथन ऐसा दिखेगा:

	![screenshot](images/pencil-gt-code.png)

+ अपने प्रोजेक्ट का परीक्षण करें; अब आपको सिलेक्टर ब्लॉक के निकट कुछ भी बना पाने में सक्षम नहीं होना चाहिए।

	![screenshot](images/paint-fixed.png)


