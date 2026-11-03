# Interview Presentation Skill

**Career Evidence · 02 / Interview Presentation**

**Turn your experience into a story you can show and explain.** Build a focused self-introduction, project case study, and role-fit presentation from real evidence—with speaker notes and a realistic time budget.

[中文说明](README.zh-CN.md) · [Worked example](examples/five-minute-interview.md) · [01 / Canada Resume](https://github.com/CHAR9S/canada-resume-skill)

## What it does

- Selects relevant experience from your resume and project notes.
- Connects your contribution to the target role.
- Plans each slide's message, visuals, and spoken explanation.
- Keeps individual contributions separate from team outcomes.
- Creates an editable PPTX when the host assistant has presentation tools; clearly reports when only a storyboard can be delivered.

This is an AI instruction package, not a standalone slide generator. It bundles no renderer, API subscription, or tracking service. File generation depends on your assistant. A presentation is useful when appropriate to the interview; it is not a universal Canadian hiring requirement.

## Quick start

Download this repository and give your assistant `skills/career-presentation/SKILL.md` and both files in `references/`, together with a redacted resume and target job description.

```text
Use the Career Presentation skill to prepare a five-minute interview presentation.
Use my resume and these project notes. Explain edits in Chinese; write slides in English.
Show my personal contribution accurately. Include speaker notes and estimated timing.
Create an editable PPTX if tools are available; otherwise identify that limitation.
```

For a Codex project, copy the complete `skills/career-presentation` folder into `.agents/skills/`, then invoke `$career-presentation`. Other clients should use their documented skill location. See [official installation guidance](https://learn.chatgpt.com/docs/build-skills). The resume skill is optional; either skill works independently.

## The workflow

**Brief → Evidence map → Case selection → Slides and notes → Fact and layout review**

Start with the employer's instructions and available time. Show evidence for the most relevant capabilities, rather than copying the whole resume onto slides. End with a clear connection to the role.

## Example

“Helped with reports” becomes a case about maintaining a weekly Excel tracker—if the candidate confirms that work. It does not become an invented efficiency improvement. See the [complete fictional storyboard](examples/five-minute-interview.md).

## Sources and limits

The shared evidence-writing approach is informed by Canadian employment-service resume training materials. The source deck teaches resumes, not interview slide design. Presentation structures and delivery guidance here are original project extensions. See [source notes](docs/sources.md) and [validation status](docs/validation.md).

The source institution is not named publicly at the contributor's request. This project does not claim institutional endorsement, co-authorship by trainers, or guaranteed interview outcomes. No source PDF is redistributed.

## About the creator

CHAR9S is an independent designer and builder with 15+ years in motion and visual design, a background in film and brand production, and experience running a creative studio. Career Evidence combines that production background with practical AI workflows. It does not claim professional recruiting credentials.

## Feedback and licence

Share fictional or redacted examples in [Discussions](https://github.com/CHAR9S/career-presentation-skill/discussions). Never post private resumes or client material. See [contribution guidance](CONTRIBUTING.md). Original project files are licensed under [MIT](LICENSE); third-party materials retain their own rights.
