## धुन बदलें

यह आपकी धुन को और अधिक रोचक बनाने का समय है! हम सिंथेसाइज़र ध्वनियों को बदलकर ऐसा कर सकते हैं जो इसका उपयोग कर रहा है। डिफ़ॉल्ट Sonic Pi सिंथ को `beep` कहा जाता है।

एक अलग सिंथ का उपयोग करने के लिए, आपको कोड `use_synth :name of synth` का उपयोग करना होगा कोड के अनुक्रम के ऊपर जिसमे आप इसका उपयोग करना चाहते हैं।

इस उदाहरण में, `fm` सिंथ का नाम है:

```ruby
use_synth :fm
2.times do
  play 60
  sleep 0.5
  play 67
  sleep 0.5
end
```

### प्रयास करने के लिए सिंथ

Sonic Pi के साथ बहुत सारे अच्छे ध्वनि वाले सिंथ शामिल हैं। उनके नाम खोजने के लिए, **help** आइकन पर क्लिक करें स्क्रीन के शीर्ष पर ताकि मदद दस्तावेज़ विंडो दिखाई दे। फिर **Synths** का चयन करें मदद विंडो के बाएँ हाथ की ओर टैब से। उपयोग करने के तरीके के बारे में अधिक जानकारी प्राप्त करने के लिए किसी भी सिंथ नाम पर क्लिक करें।