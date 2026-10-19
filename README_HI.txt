श्री कष्टभंजन देव पशु आहार करजी — Native Android Project
थीम: भगवा / ऑरेंज

महत्वपूर्ण सचाई:
- यह सोर्स प्रोजेक्ट है, तैयार APK नहीं। इस चैट के रनटाइम में Android SDK/Gradle उपलब्ध नहीं हैं, इसलिए यहां APK compile या device-test नहीं किया जा सका।
- केवल मोबाइल से मुफ्त APK बनाने के लिए इस प्रोजेक्ट को GitHub पर public repository में अपलोड किया जा सकता है। .github/workflows/build-apk.yml में GitHub Actions build workflow है। Repo में push या Actions टैब से “Build Android APK” चलाने पर app-debug.apk artifact बनना चाहिए।
- APK debug-signed होता है और sideload/testing के लिए है; Play Store release signing अलग प्रक्रिया है।
- मौजूदा native prototype में स्थानीय SQLite ग्राहक/सामान डेटा, ग्राहक क्रमांकित सूची, बिक्री पर स्टॉक कम करना, खरीद पर स्टॉक बढ़ाना, भुगतान, ग्राहक बकाया, टेक्स्ट हिसाब शेयर और CSV रिपोर्ट शेयर शामिल हैं।
- अभी पूर्ण ग्राहक-स्टेटमेंट PDF/इमेज, पूरे SQLite डेटा का JSON backup/restore, और दूसरे फोन पर डेटा import/export सुविधा पूरी नहीं है। CSV रिपोर्ट पूरा app backup नहीं है।
- डेटा फोन में ही रहता है; अपने-आप cloud sync नहीं है। APK दूसरे फोन पर भेजने से ग्राहक/लेन-देन डेटा अपने-आप नहीं जाता।
- कोई paid hosting/subscription जरूरी नहीं है, पर GitHub account/internet की जरूरत होगी। Android SDK/Gradle को GitHub Actions runner पर मुफ्त build के लिए चलाया जाता है, GitHub की वर्तमान usage limits लागू हो सकती हैं।
