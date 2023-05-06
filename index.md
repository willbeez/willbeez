---
layout: home
---
![profile picture](/assets/images/will.jpeg){: style="border-radius: 50%; width: 50%;" }
### Hi there 👋
- 🔭 I’m currently working on: <a href="https://github.com/willbeez/ESP32-WiFi-Bluetooth-Android">ESP32 AI plant health monitoring</a> and my personal website <a href="https://willbeez.com">willbeez.com</a> (<a href="https://github.com/willbeez/willbeez">GitHub link</a>)
- 🌱 I’m currently learning: <a href="https://github.com/hwchase17/langchain">LangChain</a>, <a href="https://www.pinecone.io/">Pinecone</a>, and C++ for ESP32 devices. 
- 👯 I’m looking to collaborate on: AI Projects that benifit everyone.
- 🤔 I’m looking for help with: Physical product development and Android app development
- 💬 Ask me about: if I am available for work!
- 📫 How to reach me: <a href="william12211@gmail.com">Email</a>, <a href="https://www.linkedin.com/in/william-beasley-5a1435a0/">LinkedIn</a>, <a href="https://github.com/willbeez">GitHub</a>, <a href="https://www.instagram.com/willbeez/">Instagram</a>
- 😄 Pronouns: He/Him
- ⚡ Fun fact: My hobbies include paramotoring, rock climbing, snowboarding, MTBing, and Photography.

### Blog
{% for post in site.posts %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.date | date: "%B %-d, %Y" }}</p>
  </article>
{% endfor %}