# 🎓 College Helpdesk Chatbot (IBM Watson Assistant)

This is an AI-powered college helpdesk chatbot built using IBM Watson Assistant.
It can answer queries related to:
- Courses
- Fees
- Admission
- Fallback for unknown questions

The chatbot is deployed through IBM Cloud Web Chat and can be embedded in any webpage.

---

## 🚀 Features
- Welcome Action
- Course/Fees/Admission actions
- Fallback action
- Web Chat deployment
- Conversation starters

---

## 📌 Technologies
- IBM Cloud
- IBM Watson Assistant
- Web Chat Integration
- HTML/CSS

---

## 📥 How to Use
1. Open the embed.html file in a browser  
2. The chatbot will load automatically  
3. Ask: “courses”, “fees”, “admission”, etc.

---

## 💻 Embed Code (replace your IDs)
```html
<script>
  window.watsonAssistantChatOptions = {
    integrationID: "YOUR-INTEGRATION-ID",
    region: "YOUR-REGION",
    serviceInstanceID: "YOUR-SERVICE-ID",
    onLoad: function(instance) { instance.render(); }
  };
</script>
<script src="https://web-chat.global.assistant.watson.appdomain.cloud/loadWatsonAssistantChat.js"></script>
