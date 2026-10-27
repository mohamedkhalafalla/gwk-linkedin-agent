<p align="center">
  <img src="docs/assets/og.png" alt="LinkedIn Agent Skill: شرح بالمصري من Grow With Khalaf" width="100%">
</p>

<div dir="rtl">

# LinkedIn Agent Skill: الشرح بالمصري

ده شرح من **Grow With Khalaf** بالمصري لـ [LinkedIn Agent Skill](https://github.com/Jakeschincariol/linkedin-agent-skill)، وهي 11 skill ببلاش لـ Claude من عمل **Jake Schincariol**. بتكتبلك بوستات LinkedIn، وتقيّم بروفايلك من 100، وتخطط أسبوعك، وتساعدك ترد على الكومنتات والرسايل.

**الدليل الكامل وطريقة التسطيب خطوة بخطوة: [mohamedkhalafalla.github.io/gwk-linkedin-agent](https://mohamedkhalafalla.github.io/gwk-linkedin-agent/)**

> **الكريديت:** الـ skills كلها من عمل Jake Schincariol ([opusjake.ai](https://opusjake.ai))، ومنشورة برخصة MIT في [الريبو الأصلي](https://github.com/Jakeschincariol/linkedin-agent-skill). إحنا مش تبعه. الريبو ده فيه الشرح بس، ونسخ zip جاهزة لـ claude.ai فيها نفس ملفاته من غير تعديل ومعاها رخصته.

> **مش بيدخل على حساب LinkedIn بتاعك ولا بينزّل حاجة.** كل skill بتطلّعلك نص جاهز تنسخه وتنزّله بإيدك.

## التسطيب على Claude Code

من الريبو الأصلي:

</div>

```bash
git clone https://github.com/Jakeschincariol/linkedin-agent-skill.git
cp -r linkedin-agent-skill/skills/li-* ~/.claude/skills/
```

<div dir="rtl">

أو كـ plugin:

</div>

```
/plugin marketplace add Jakeschincariol/linkedin-agent-skill
/plugin install linkedin-agent
```

<div dir="rtl">

## التسطيب على claude.ai

1. شغّل **Code execution and file creation** من **Settings ← Capabilities**.
2. نزّل [`linkedin-agent-all.zip`](docs/downloads/linkedin-agent-all.zip)، وافتحه. جواه 11 ملف zip، واحد لكل skill.
3. ارفع كل zip زي ما هو من **Customize ← Skills ← + ← Create skill ← Upload a skill**.

## جوه الريبو

| المسار | فيه إيه |
|---|---|
| `docs/index.html` | صفحة الدليل (GitHub Pages) |
| `docs/downloads/` | ملف zip لكل skill، وملف فيه الـ 11، وقالب `voice.md` |
| `LICENSE` | رخصة MIT الأصلية بتاعة Jake Schincariol |

## الرخصة

الـ skills اللي في `docs/downloads/` من عمل Jake Schincariol برخصة MIT (شوف `LICENSE`). الشرح من Grow With Khalaf. مش تابعين لـ Jake Schincariol ولا Anthropic ولا LinkedIn.

</div>

---

**English:** An Egyptian Arabic install guide by Grow With Khalaf for Jake Schincariol's [LinkedIn Agent Skill](https://github.com/Jakeschincariol/linkedin-agent-skill) (MIT). All skills are his work. This repo only adds the guide page and unmodified claude.ai upload zips that keep his license. Not affiliated with Jake Schincariol, Anthropic or LinkedIn.
