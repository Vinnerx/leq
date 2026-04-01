# LEQ Resources
This repository collects different interactive digital learning resources related to the Learning Experience Questionnaire course evaluation process, as described by Borglund et al. (2023).

# Prompt used
Create a self-contained single-page HTML learning resource based on the LEQ (Learning Experience Questionnaire) guide from Umeå University’s Centre for Educational Development.

The resource should not only present the guide, but help university teachers understand and use LEQ for systematic, collegial, and scientific course evaluation and course development. It should function as a pedagogically supportive digital learning resource, not just an interactive dashboard.

The page should support self-paced exploration and gradual understanding. Prioritise pedagogical clarity, interpretive support, and academic usability over decorative design.

Include these sections:
1. Overview
2. The LEQ Process
3. The Questionnaire
4. Practical Instructions
5. Course Analysis Forms

Use smooth in-page navigation via a top navigation bar or sidebar.

Required features:

1. Overview
- Briefly explain the purpose of the LEQ guide.
- Clarify that LEQ examines prerequisites for student learning based on empirically grounded learning factors.
- State that the guide supports course evaluation and course development, and that the appendices explain the theoretical structure of LEQ and include forms for course analysis and course reflection.

2. The LEQ Process
- Present the 6-step LEQ process as an interactive flowchart.
- The steps should be:
  1) New course offering
  2) Course survey using LEQ
  3) Students’ course reflection, optional
  4) Course analysis, draft to meeting to final
  5) Competence development
  6) Course development
- Each step should be clickable and reveal:
  - what happens in that step,
  - its purpose,
  - and how it connects to the next step.
- Show the optional student course reflection as a dashed visual loop.
- Emphasise that LEQ is an ongoing development cycle, not just an administrative routine.

3. The Questionnaire
- Present the 15 learning factors, a to o, as interactive cards grouped under:
  - Meaningfulness, statements 1 to 7
  - Comprehensibility, statements 8 to 16
  - Manageability, statements 17 to 22
- Use warm colour coding for Meaningfulness, cool blue for Comprehensibility, and green for Manageability.
- Clicking a card should reveal:
  - the learning factor description,
  - the corresponding LEQ statement or statements,
  - the statement number or numbers,
  - and a short explanation of why the factor matters for understanding the learning environment.
- Make the relationship between learning factors, statements, and the three dimensions easy to understand.

4. Polar Diagram Explainer
- Include an interactive SVG radar or polar chart using statements 1 to 22 as axes.
- On hover, show:
  - statement number,
  - full statement text,
  - and its dimension.
- Add a brief explanation of interpretation:
  - points further from the centre indicate that more students considered the statement to be true,
  - a larger circular shape suggests a more beneficial learning environment in terms of the underlying learning factors,
  - weaker aspects are not automatically problems to fix,
  - and the diagram is a support for analysis, not a normative judgement.
- Note that statement 23, own effort, is not included in the polar diagram.

5. Practical Instructions
- Present Course Survey, Course Reflection, Course Analysis, and Course Analysis Meeting as accordion sections.
- Each section should include:
  - a short explanation of purpose,
  - relevant support resources or tools such as Canvas, Survey&Report, and UmU Play where applicable,
  - and the tips and advice from the guide as bullet lists.

6. Course Analysis Meeting
- Show the four-round agenda as a visual timeline or stepper:
  1) Presentation of the pedagogical structure
  2) Stronger and weaker aspects of the learning environment
  3) Discussion of possible course development
  4) Final reflection
- On click or hover, show a short explanation of the purpose of each round.
- Also include key conditions from the guide:
  - different courses are usually preferable,
  - participants should prepare a preliminary course analysis,
  - the chairperson facilitates rather than presents,
  - the purpose is collegial exchange of concrete teaching experience,
  - and LEQ is an aid to analysis, not a normative judgement tool.

7. Course Analysis Forms
- Present the two appendix forms in a readable and pedagogically useful way:
  - Form for course analysis
  - Form for course reflection
- Group the form items into meaningful categories rather than just listing them.
- Briefly explain what each part of the form helps the teacher or student group do.

Pedagogical design principles:
- Use progressive disclosure, so users first see the big picture and can then open more detailed explanation.
- Include brief explanatory microtexts such as:
  - Why this matters
  - Interpret with care
  - In practice
- Help users understand not only what LEQ contains, but how its parts relate and how the material can be used.

Design requirements:
- Use Umeå University-inspired colours, with a dark navy or teal header, white content areas, and restrained academic styling.
- Make the page mobile-friendly and readable.
- Use accessible interactions and clear hierarchy.
- Fully self-contained HTML only, no external dependencies unless absolutely necessary.
- Do not invent content.
- All text must come from the document or be directly derived from it through concise explanatory phrasing.

Include the source credit clearly:
“Centre for Educational Development, Umeå University, Edition 3, 2023"
