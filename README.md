# हैकट्रिक्स क्लाउड

<details>

<summary><strong>जानें AWS हैकिंग को शून्य से हीरो तक</strong> <a href="https://training.hacktricks.xyz/courses/arte"><strong>htARTE (हैकट्रिक्स AWS रेड टीम एक्सपर्ट)</strong></a><strong> के साथ!</strong></summary>

हैकट्रिक्स का समर्थन करने के अन्य तरीके:

* यदि आप अपनी **कंपनी का विज्ञापन हैकट्रिक्स में देखना चाहते हैं** या **हैकट्रिक्स को PDF में डाउनलोड करना चाहते हैं** तो [**सब्सक्रिप्शन प्लान्स देखें**](https://github.com/sponsors/carlospolop)!
* [**आधिकारिक PEASS और हैकट्रिक्स स्वैग**](https://peass.creator-spring.com) प्राप्त करें
* [**द पीएस फैमिली**](https://opensea.io/collection/the-peass-family) की खोज करें, हमारा विशेष [**NFTs**](https://opensea.io/collection/the-peass-family) संग्रह
* **शामिल हों** 💬 [**डिस्कॉर्ड ग्रुप**](https://discord.gg/hRep4RUj7f) या [**टेलीग्राम ग्रुप**](https://t.me/peass) या **मुझे** ट्विटर पर **फॉलो** करें 🐦 [**@hacktricks\_live**](https://twitter.com/hacktricks\_live)**.**
* **अपने हैकिंग ट्रिक्स को सबमिट करके साझा करें** [**HackTricks**](https://github.com/carlospolop/hacktricks) और [**HackTricks Cloud**](https://github.com/carlospolop/hacktricks-cloud) github repos.

</details>

<figure><img src=".gitbook/assets/cloud.gif" alt=""><figcaption></figcaption></figure>

_हैकट्रिक्स लोगो और मोशन डिजाइन किया गया_ [_@ppiernacho_](https://www.instagram.com/ppieranacho/)_._

{% hint style="success" %}
वेलकम टू द पेज वेर यू विल फाइंड इच **हैकिंग ट्रिक/तकनीक/व्हेटेवर संबंधित टू सीआई/सीडी एंड क्लाउड** आई हैव लर्न्ट इन **सीटीएफ्स**, **रियल** लाइफ **एनवायरमेंट्स**, **रिसर्चिंग**, एंड **रीडिंग** रिसर्चेस एंड न्यूज़।
{% endhint %}

## **पेंटेस्टिंग सीआई/सीडी मेथडोलॉजी**

**हैकट्रिक्स सीआई/सीडी मेथडोलॉजी में आपको सीआई/सीडी गतिविधियों से संबंधित इंफ्रास्ट्रक्चर को पेंटेस्ट करने का तरीका मिलेगा।** एक **परिचय** के लिए निम्नलिखित पेज पढ़ें:

{% content-ref url="pentesting-ci-cd/pentesting-ci-cd-methodology.md" %}
[pentesting-ci-cd-methodology.md](pentesting-ci-cd/pentesting-ci-cd-methodology.md)
{% endcontent-ref %}

## पेंटेस्टिंग क्लाउड मेथडोलॉजी

**हैकट्रिक्स क्लाउड मेथडोलॉजी में आपको क्लाउड वातावरणों को पेंटेस्ट करने का तरीका मिलेगा।** एक **परिचय** के लिए निम्नलिखित पेज पढ़ें:

{% content-ref url="pentesting-cloud/pentesting-cloud-methodology.md" %}
[pentesting-cloud-methodology.md](pentesting-cloud/pentesting-cloud-methodology.md)
{% endcontent-ref %}

## लाइसेंस और डिसक्लेमर

**इन्हें चेक करें:**

{% content-ref url="https://app.gitbook.com/s/-L_2uGJGU7AVNRcqRvEi/welcome/hacktricks-values-and-faq" %}
[हैकट्रिक्स मूल्य और FAQ](https://app.gitbook.com/s/-L\_2uGJGU7AVNRcqRvEi/welcome/hacktricks-values-and-faq)
{% endcontent-ref %}

## गिटहब स्टैट्स

![हैकट्रिक्स क्लाउड गिटहब स्टैट्स](https://repobeats.axiom.co/api/embed/1dfdbb0435f74afa9803cd863f01daac17cda336.svg "रिपोबीट्स एनालिटिक्स इमेज") 

<details>

<summary><strong>जानें AWS हैकिंग को शून्य से हीरो तक</strong> <a href="https://training.hacktricks.xyz/courses/arte"><strong>htARTE (हैकट्रिक्स AWS रेड टीम एक्सपर्ट)</strong></a><strong> के साथ!</strong></summary>

हैकट्रिक्स का समर्थन करने के अन्य तरीके:

* यदि आप अपनी **कंपनी का विज्ञापन हैकट्रिक्स में देखना चाहते हैं** या **हैकट्रिक्स को PDF में डाउनलोड करना चाहते हैं** तो [**सब्सक्रिप्शन प्लान्स देखें**](https://github.com/sponsors/carlospolop)!
* [**आधिकारिक PEASS और हैकट्रिक्स स्वैग**](https://peass.creator-spring.com) प्राप्त करें
* [**द पीएस फैमिली**](https://opensea.io/collection/the-peass-family) की खोज करें, हमारा विशेष [**NFTs**](https://opensea.io/collection/the-peass-family) संग्रह
* **शामिल हों** 💬 [**डिस्कॉर्ड ग्रुप**](https://discord.gg/hRep4RUj7f) या [**टेलीग्राम ग्रुप**](https://t.me/peass) या **मुझे** ट्विटर पर **फॉलो** करें 🐦 [**@hacktricks\_live**](https://twitter.com/hacktricks\_live)**.**
* **अपने हैकिंग ट्रिक्स को सबमिट करके साझा करें** [**HackTricks**](https://github.com/carlospolop/hacktricks) और [**HackTricks Cloud**](https://github.com/carlospolop/hacktricks-cloud) github repos.

</details>
