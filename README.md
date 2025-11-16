# From Idea to MVP: Supercharging App Development with Gemini CLI & Google Stitch - #DevFestAhm 2025 Workshop

GDG Ahmedabad - Gemini CLI Workshop by Pratik Butani &amp; Ravi Rupareliya

## Workshop Overview

This hands-on workshop demonstrates how to transform a simple idea into a working Flutter MVP using Google's Gemini CLI and Google Stitch. 

## MVP Idea:
We'll build a **LinkedIn Post Generator for Community Events** - a practical tool that helps community members create engaging social media content about their event experiences.

1. Generate MVP Requirements with Gemini
```
Act as a senior product owner and Help me prepare mvp for this requirement.
Received a requirement from GDG Ahmedabad community for "LinkedIn post generator for events". Basically there will be 4-5 community in initial stage, user will select one from those, and add personalized message in input box.
```

2. Generate Design Prompts for Google Stitch
```
I want to create a mockup design for this mvp version, help me create prompt for the same. I will utilise that prompt in Google Stitch. No need to provide image sample.
```

3. Create project in Gemini CLI
```
I would like to implement a post generation in @code.html where Gemini API {api-key} will be used and based on selected event we will generate the linkedIn post. Use gemini-2.5-flash model
```

4. Create Project through Gemini CLI
```
Follow the instructions from @instructions.md and populate the selector with appropriate values. Use the description of the selected value as the hidden base context for LinkedIn post generation. Do not reveal these details to the user. If the user provides any input, treat it as a personalized context and blend it with the base context.
Ensure the generated LinkedIn post dynamically adapts based on whether the user’s intent is pre-event or post-event. The post should be optimized for higher reach and engagement, with a word limit of 150 words. Do not include any extra lines or text before or after the generated content.
```


### Obtain Gemini API Key

1. Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Create or select a project
3. Generate an API key
4. Copy the API key securely

### Manual API Key Configuration

**Security Note:** 
- Never commit API keys to version control


## Additional Resources

### Documentation Links
- [Flutter Documentation](https://docs.flutter.dev/)
- [Gemini API Documentation](https://ai.google.dev/docs)
- [Google Stitch Documentation](https://stitch.google.com/docs)
- [Gemini CLI Documentation](https://github.com/google/gemini-cli)
- [Gemini CLI: Custom slash commands](https://cloud.google.com/blog/topics/developers-practitioners/gemini-cli-custom-slash-commands)


---

## Post-Workshop Action Items

### For Attendees
1. Clone the generated project
2. Set up their own Gemini API key
3. Customize for their own community needs
4. Explore extending features (image generation, multi-language support)

### Possible Extensions
- Add image generation for posts
- Multi-language post generation
- Integration with LinkedIn API for direct posting
- Analytics dashboard for community managers
- Template library for different event types

---

## Conclusion

This workshop demonstrates the practical application of AI tools in modern app development, showing how developers can leverage Gemini CLI and Google Stitch to accelerate the journey from idea to MVP. The resulting application provides real value to tech communities while showcasing the power of AI-assisted development.

> **Remember:** AI tools are accelerators, not replacements. Understanding fundamentals remains crucial for creating robust, maintainable applications.

---

## Contributors
### Ravi Rupareliya
[LinkedIn](https://www.linkedin.com/in/ravi-rupareliya) | [Topmate](https://topmate.io/ravi_rupareliya) | [Medium](https://ravirupareliya.medium.com/) | [Personal](https://ravirupareliya.com)


### Pratik Butani
[LinkedIn](https://www.linkedin.com/in/pratikbutani) | [Topmate](https://topmate.io/pratikbutani) | [Medium](https://pratikbutani.medium.com/)

What I developed through AI till now:

- https://done.pratikbutani.com/
- https://navkar.pratikbutani.com/
- https://kshma.pratikbutani.com
- https://digipin.pratikbutani.com/
- https://drive.google.com/drive/folders/12KlROd8MPfR0dbxGWoDUcG5Z-TBCoBQ_?usp=drive_link + MyGPT
- https://pratikbutani.github.io/win-or-die/

What are the tools that I’ve used:

- https://manus.im/
- https://aistudio.google.com/apps
- https://gemini.google.com
- https://computerx.ai/
- https://www.task-master.dev/
- https://github.com/google-gemini/gemini-cli
- https://www.granola.ai/
- https://www.coderabbit.ai/
- https://grok.com/
- https://app.napkin.ai/page/create
- https://claude.ai/
- https://notebooklm.google/
- https://gamma.app/
- https://stanley.stan.store/ - **PAID**
- https://stitch.withgoogle.com/ + https://discuss.ai.google.dev/t/stitch-prompt-guide/83844
- https://rows.com/

**Questions?** Feel free to reach out during or after the workshop!

---

*Last Updated: November 2025*  
*DevFest Ahmedabad 2025*
