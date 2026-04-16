🌐 यह एक स्वचालित अनुवाद है। समुदाय से सुधार का स्वागत है!

---
<h1 align="center">
  <br>
  <a href="https://github.com/thedotmack/claude-mem">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/thedotmack/claude-mem/main/docs/public/claude-mem-logo-for-dark-mode.webp">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/thedotmack/claude-mem/main/docs/public/claude-mem-logo-for-light-mode.webp">
      <img src="https://raw.githubusercontent.com/thedotmack/claude-mem/main/docs/public/claude-mem-logo-for-light-mode.webp" alt="Claude-Mem" width="400">
    </picture>
  </a>
  <br>
</h1>

<p align="center">
  <a href="README.zh.md">🇨🇳 中文</a> •
  <a href="README.zh-tw.md">🇹🇼 繁體中文</a> •
  <a href="README.ja.md">🇯🇵 日本語</a> •
  <a href="README.pt-br.md">🇧🇷 Português</a> •
  <a href="README.ko.md">🇰🇷 한국어</a> •
  <a href="README.es.md">🇪🇸 Español</a> •
  <a href="README.de.md">🇩🇪 Deutsch</a> •
  <a href="README.fr.md">🇫🇷 Français</a>
  <a href="README.he.md">🇮🇱 עברית</a> •
  <a href="README.ar.md">🇸🇦 العربية</a> •
  <a href="README.ru.md">🇷🇺 Русский</a> •
  <a href="README.pl.md">🇵🇱 Polski</a> •
  <a href="README.cs.md">🇨🇿 Čeština</a> •
  <a href="README.nl.md">🇳🇱 Nederlands</a> •
  <a href="README.tr.md">🇹🇷 Türkçe</a> •
  <a href="README.uk.md">🇺🇦 Українська</a> •
  <a href="README.vi.md">🇻🇳 Tiếng Việt</a> •
  <a href="README.id.md">🇮🇩 Indonesia</a> •
  <a href="README.th.md">🇹🇭 ไทย</a> •
  <a href="README.hi.md">🇮🇳 हिन्दी</a> •
  <a href="README.bn.md">🇧🇩 বাংলা</a> •
  <a href="README.ur.md">🇵🇰 اردو</a> •
  <a href="README.ro.md">🇷🇴 Română</a> •
  <a href="README.sv.md">🇸🇪 Svenska</a> •
  <a href="README.it.md">🇮🇹 Italiano</a> •
  <a href="README.el.md">🇬🇷 Ελληνικά</a> •
  <a href="README.hu.md">🇭🇺 Magyar</a> •
  <a href="README.fi.md">🇫🇮 Suomi</a> •
  <a href="README.da.md">🇩🇰 Dansk</a> •
  <a href="README.no.md">🇳🇴 Norsk</a>
</p>

<h4 align="center"><a href="https://claude.com/claude-code" target="_blank">Claude Code</a> के लिए निर्मित स्थायी स्मृति संपीड़न प्रणाली।</h4>

<p align="center">
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-AGPL%203.0-blue.svg" alt="अनुज्ञापत्र">
  </a>
  <a href="package.json">
    <img src="https://img.shields.io/badge/version-6.5.0-green.svg" alt="संस्करण">
  </a>
  <a href="package.json">
    <img src="https://img.shields.io/badge/node-%3E%3D18.0.0-brightgreen.svg" alt="Node">
  </a>
  <a href="https://github.com/thedotmack/awesome-claude-code">
    <img src="https://awesome.re/mentioned-badge.svg" alt="Awesome Claude Code में उल्लेखित">
  </a>
</p>

<p align="center">
  <a href="https://trendshift.io/repositories/15496" target="_blank">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/thedotmack/claude-mem/main/docs/public/trendshift-badge-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/thedotmack/claude-mem/main/docs/public/trendshift-badge.svg">
      <img src="https://raw.githubusercontent.com/thedotmack/claude-mem/main/docs/public/trendshift-badge.svg" alt="thedotmack/claude-mem | Trendshift" width="250" height="55"/>
    </picture>
  </a>
</p>

<br>

<p align="center">
  <a href="https://github.com/thedotmack/claude-mem">
    <picture>
      <img src="https://raw.githubusercontent.com/thedotmack/claude-mem/main/docs/public/cm-preview.gif" alt="Claude-Mem पूर्वावलोकन" width="800">
    </picture>
  </a>
</p>

<p align="center">
  <a href="#त्वरित-आरंभ">त्वरित आरंभ</a> •
  <a href="#यह-कैसे-काम-करता-है">यह कैसे काम करता है</a> •
  <a href="#खोज-उपकरण">खोज उपकरण</a> •
  <a href="#प्रलेखन">प्रलेखन</a> •
  <a href="#विन्यास">विन्यास</a> •
  <a href="#समस्या-निवारण">समस्या निवारण</a> •
  <a href="#अनुज्ञापत्र">अनुज्ञापत्र</a>
</p>

<p align="center">
  Claude-Mem स्वचालित रूप से उपकरण उपयोग के अवलोकनों को अधिगृहीत करके, शब्दार्थिक सारांश उत्पन्न करके, और उन्हें भविष्य के सत्रों के लिए उपलब्ध कराकर सत्रों में संदर्भ को निर्बाध रूप से संरक्षित करता है। यह Claude को परियोजनाओं के बारे में ज्ञान की निरंतरता बनाए रखने में सक्षम बनाता है, भले ही सत्र समाप्त हो जाएं या पुनः जुड़ जाएं।
</p>

---

## त्वरित आरंभ

टर्मिनल में एक नया Claude Code सत्र आरंभ करें और निम्नलिखित आदेश दर्ज करें:

```
> /plugin marketplace add thedotmack/claude-mem

> /plugin install claude-mem
```

Claude Code को पुनः आरंभ करें। पिछले सत्रों का संदर्भ स्वचालित रूप से नए सत्रों में दिखाई देगा।

**मुख्य विशेषताएं:**

- 🧠 **स्थायी स्मृति** - संदर्भ सत्रों में बना रहता है
- 📊 **प्रगतिशील प्रकटीकरण** - टोकन लागत दृश्यता के साथ स्तरित स्मृति पुनर्प्राप्ति
- 🔍 **कौशल-आधारित खोज** - mem-search कौशल के साथ अपनी परियोजना के इतिहास में पूछताछ करें
- 🖥️ **वेब दर्शक** - http://localhost:37777 पर वास्तविक समय स्मृति प्रवाह
- 💻 **Claude Desktop कौशल** - Claude Desktop वार्तालापों से स्मृति खोजें
- 🔒 **गोपनीयता नियंत्रण** - संवेदनशील सामग्री को संग्रहण से बाहर रखने के लिए `<private>` चिह्न का उपयोग करें
- ⚙️ **संदर्भ विन्यास** - किस संदर्भ को प्रविष्ट किया जाता है, इस पर सूक्ष्म नियंत्रण
- 🤖 **स्वचालित संचालन** - हस्तचालित हस्तक्षेप की आवश्यकता नहीं
- 🔗 **उद्धरण** - पहचान संख्याओं के साथ पिछले अवलोकनों का संदर्भ दें (http://localhost:37777/api/observation/{id} के माध्यम से अभिगम करें या http://localhost:37777 पर वेब दर्शक में सभी देखें)
- 🧪 **बीटा माध्यम** - संस्करण परिवर्तन के माध्यम से Endless Mode जैसी प्रायोगिक सुविधाओं को आज़माएं

---

## प्रलेखन

📚 **[संपूर्ण प्रलेखन देखें](https://docs.claude-mem.ai/)** - आधिकारिक वेबसाइट पर अवलोकन करें

### आरंभ करना

- **[स्थापना मार्गदर्शिका](https://docs.claude-mem.ai/installation)** - त्वरित आरंभ और उन्नत स्थापना
- **[उपयोग मार्गदर्शिका](https://docs.claude-mem.ai/usage/getting-started)** - Claude-Mem स्वचालित रूप से कैसे काम करता है
- **[खोज उपकरण](https://docs.claude-mem.ai/usage/search-tools)** - प्राकृतिक भाषा के साथ अपनी परियोजना के इतिहास में पूछताछ करें
- **[बीटा सुविधाएं](https://docs.claude-mem.ai/beta-features)** - Endless Mode जैसी प्रायोगिक सुविधाओं को आज़माएं

### सर्वोत्तम अभ्यास

- **[संदर्भ अभियांत्रिकी](https://docs.claude-mem.ai/context-engineering)** - कृत्रिम बुद्धिमत्ता अभिकर्ता संदर्भ अनुकूलन सिद्धांत
- **[प्रगतिशील प्रकटीकरण](https://docs.claude-mem.ai/progressive-disclosure)** - Claude-Mem की संदर्भ प्राइमिंग रणनीति के पीछे का दर्शन

### वास्तुकला

- **[अवलोकन](https://docs.claude-mem.ai/architecture/overview)** - प्रणाली घटक और आँकड़ा प्रवाह
- **[वास्तुकला विकास](https://docs.claude-mem.ai/architecture-evolution)** - v3 से v5 तक की यात्रा
- **[हुक वास्तुकला](https://docs.claude-mem.ai/hooks-architecture)** - Claude-Mem जीवनचक्र हुक का उपयोग कैसे करता है
- **[हुक संदर्भ](https://docs.claude-mem.ai/architecture/hooks)** - 7 हुक लिपियाँ समझाई गईं
- **[कार्यकर्ता सेवा](https://docs.claude-mem.ai/architecture/worker-service)** - HTTP API और Bun प्रबंधन
- **[आँकड़ाकोष](https://docs.claude-mem.ai/architecture/database)** - SQLite योजनाबद्ध संरचना और FTS5 खोज
- **[खोज वास्तुकला](https://docs.claude-mem.ai/architecture/search-architecture)** - Chroma सदिश आँकड़ाकोष के साथ संकर खोज

### विन्यास और विकास

- **[विन्यास](https://docs.claude-mem.ai/configuration)** - परिवेश चर और सेटिंग्स
- **[विकास](https://docs.claude-mem.ai/development)** - निर्माण, परीक्षण, योगदान
- **[समस्या निवारण](https://docs.claude-mem.ai/troubleshooting)** - सामान्य समस्याएं और समाधान

---

## यह कैसे काम करता है

**मुख्य घटक:**

1. **5 जीवनचक्र हुक** - SessionStart, UserPromptSubmit, PostToolUse, Stop, SessionEnd (6 हुक लिपियाँ)
2. **बुद्धिमान स्थापना** - पूर्वसंचित निर्भरता जाँचकर्ता (पूर्व-हुक लिपि, जीवनचक्र हुक नहीं)
3. **कार्यकर्ता सेवा** - वेब दर्शक और 10 खोज समापन बिंदुओं के साथ पोर्ट 37777 पर HTTP API, Bun द्वारा प्रबंधित
4. **SQLite आँकड़ाकोष** - सत्र, अवलोकन, सारांश संग्रहीत करता है
5. **mem-search कौशल** - प्रगतिशील प्रकटीकरण के साथ प्राकृतिक भाषा पूछताछ
6. **Chroma सदिश आँकड़ाकोष** - बुद्धिमान संदर्भ पुनर्प्राप्ति के लिए संकर शब्दार्थिक + कुंजीशब्द खोज

विवरण के लिए [वास्तुकला अवलोकन](https://docs.claude-mem.ai/architecture/overview) देखें।

---

## mem-search कौशल

Claude-Mem mem-search कौशल के माध्यम से बुद्धिमान खोज प्रदान करता है जो स्वचालित रूप से सक्रिय हो जाती है जब आप पिछले कार्य के बारे में पूछते हैं:

**यह कैसे काम करता है:**
- बस स्वाभाविक रूप से पूछें: *"हमने पिछले सत्र में क्या किया?"* या *"क्या हमने पहले इस दोष को ठीक किया था?"*
- Claude स्वचालित रूप से प्रासंगिक संदर्भ खोजने के लिए mem-search कौशल को सक्रिय करता है

**उपलब्ध खोज संक्रियाएं:**

1. **अवलोकन खोजें** - अवलोकनों में पूर्ण-पाठ खोज
2. **सत्र खोजें** - सत्र सारांशों में पूर्ण-पाठ खोज
3. **संकेत खोजें** - मूल उपयोगकर्ता अनुरोध खोजें
4. **अवधारणा द्वारा** - अवधारणा चिह्नों द्वारा खोजें (discovery, problem-solution, pattern, आदि)
5. **संचिका द्वारा** - विशिष्ट संचिकाओं का संदर्भ देने वाले अवलोकन खोजें
6. **प्रकार द्वारा** - प्रकार द्वारा खोजें (decision, bugfix, feature, refactor, discovery, change)
7. **हालिया संदर्भ** - एक परियोजना के लिए हालिया सत्र संदर्भ प्राप्त करें
8. **समयरेखा** - समय में एक विशिष्ट बिंदु के आसपास संदर्भ की एकीकृत समयरेखा प्राप्त करें
9. **पूछताछ द्वारा समयरेखा** - अवलोकनों को खोजें और सर्वश्रेष्ठ मिलान के आसपास समयरेखा संदर्भ प्राप्त करें
10. **API सहायता** - खोज API प्रलेखन प्राप्त करें

**प्राकृतिक भाषा पूछताछ के उदाहरण:**

```
"पिछले सत्र में हमने कौन से दोष ठीक किए?"
"हमने प्रमाणीकरण कैसे क्रियान्वित किया?"
"worker-service.ts में क्या परिवर्तन किए गए?"
"इस परियोजना पर हालिया कार्य दिखाएं"
"जब हमने दर्शक अंतरापृष्ठ जोड़ा तब क्या हो रहा था?"
```

विस्तृत उदाहरणों के लिए [खोज उपकरण मार्गदर्शिका](https://docs.claude-mem.ai/usage/search-tools) देखें।

---

## बीटा सुविधाएं

Claude-Mem **बीटा माध्यम** के साथ **Endless Mode** (विस्तारित सत्रों के लिए जैव-अनुकृत स्मृति वास्तुकला) जैसी प्रायोगिक सुविधाएं प्रदान करता है। http://localhost:37777 → Settings पर वेब दर्शक से स्थिर और बीटा संस्करणों के बीच परिवर्तन करें।

Endless Mode के विवरण और इसे आज़माने के तरीके के लिए **[बीटा सुविधाएं प्रलेखन](https://docs.claude-mem.ai/beta-features)** देखें।

---

## प्रणाली आवश्यकताएं

- **Node.js**: 18.0.0 या उच्चतर
- **Claude Code**: प्लगइन समर्थन के साथ नवीनतम संस्करण
- **Bun**: JavaScript चालन परिवेश और प्रक्रिया प्रबंधक (अनुपस्थित होने पर स्वतः स्थापित)
- **uv**: सदिश खोज के लिए Python संकुल प्रबंधक (अनुपस्थित होने पर स्वतः स्थापित)
- **SQLite 3**: स्थायी संग्रहण के लिए (सम्मिलित)

---

## विन्यास

सेटिंग्स `~/.claude-mem/settings.json` में प्रबंधित की जाती हैं (प्रथम बार चलाने पर पूर्वनिर्धारित मानों के साथ स्वतः निर्मित)। कृत्रिम बुद्धिमत्ता प्रतिरूप, कार्यकर्ता पोर्ट, आँकड़ा निर्देशिका, अभिलेख स्तर, और संदर्भ प्रविष्टि सेटिंग्स विन्यस्त करें।

सभी उपलब्ध सेटिंग्स और उदाहरणों के लिए **[विन्यास मार्गदर्शिका](https://docs.claude-mem.ai/configuration)** देखें।

---

## विकास

निर्माण निर्देश, परीक्षण, और योगदान कार्यप्रवाह के लिए **[विकास मार्गदर्शिका](https://docs.claude-mem.ai/development)** देखें।

---

## समस्या निवारण

यदि समस्याओं का सामना कर रहे हैं, तो Claude को समस्या का वर्णन करें और समस्या निवारण कौशल स्वचालित रूप से निदान करेगा और सुधार प्रदान करेगा।

सामान्य समस्याओं और समाधानों के लिए **[समस्या निवारण मार्गदर्शिका](https://docs.claude-mem.ai/troubleshooting)** देखें।

---

## दोष प्रतिवेदन

स्वचालित जनित्र के साथ व्यापक दोष प्रतिवेदन तैयार करें:

```bash
cd ~/.claude/plugins/marketplaces/thedotmack
npm run bug-report
```

## योगदान

योगदान का स्वागत है! कृपया:

1. भंडार का प्रतिरूप बनाएं
2. एक सुविधा शाखा बनाएं
3. परीक्षणों के साथ अपने परिवर्तन करें
4. प्रलेखन अद्यतन करें
5. एक विलय अनुरोध प्रस्तुत करें

योगदान कार्यप्रवाह के लिए [विकास मार्गदर्शिका](https://docs.claude-mem.ai/development) देखें।

---

## अनुज्ञापत्र

यह परियोजना **GNU Affero General Public License v3.0** (AGPL-3.0) के अंतर्गत अनुज्ञापत्रित है।

प्रतिलिप्यधिकार (C) 2025 Alex Newman (@thedotmack)। सर्वाधिकार सुरक्षित।

पूर्ण विवरण के लिए [LICENSE](LICENSE) संचिका देखें।

**इसका क्या अर्थ है:**

- आप इस सॉफ़्टवेयर को स्वतंत्र रूप से उपयोग, संशोधित और वितरित कर सकते हैं
- यदि आप संशोधित करके नेटवर्क परिसेवक पर तैनात करते हैं, तो आपको अपना स्रोत कूट उपलब्ध कराना होगा
- व्युत्पन्न कार्यों को भी AGPL-3.0 के अंतर्गत अनुज्ञापत्रित होना आवश्यक है
- इस सॉफ़्टवेयर के लिए कोई प्रत्याभूति नहीं है

**Ragtime पर टिप्पणी**: `ragtime/` निर्देशिका को **PolyForm Noncommercial License 1.0.0** के अंतर्गत पृथक रूप से अनुज्ञापत्रित किया गया है। विवरण के लिए [ragtime/LICENSE](ragtime/LICENSE) देखें।

---

## सहायता

- **प्रलेखन**: [docs/](docs/)
- **समस्याएं**: [GitHub Issues](https://github.com/thedotmack/claude-mem/issues)
- **भंडार**: [github.com/thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)
- **लेखक**: Alex Newman ([@thedotmack](https://github.com/thedotmack))

---

**Claude Agent SDK के साथ निर्मित** | **Claude Code द्वारा संचालित** | **TypeScript के साथ रचित**
