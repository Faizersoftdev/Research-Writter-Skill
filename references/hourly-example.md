# Example mapping: Hourly (DO NOT transfer facts into other studies)

Approved working topic in the conversation: **Hourly: Teacher Attendance and Salary Monitoring System**; teacher-side Android app that documents time-in/time-out photo evidence, matches sessions, computes session duration and *expected* compensation from an applicable historical hourly rate, and shows daily/monthly summaries. It is not official institutional payroll. Main operations are offline; optional local AI and separate website/update service are not required for core salary calculation.

Example general objective: develop an offline Android system to help teachers record teaching hours and calculate expected earnings. Sample specific objectives: attendance capture; session pairing; expected salary computation; monitoring of sessions/photos/previous rates/summaries; protection of time records; ISO 9126 evaluation.

Chosen development model for this example: **four-stage RAD** — Requirements Planning, User Design, Construction, Cutover. General-to-specific explanation uses a diagram insertion after introducing all stages, then separate explanations for each phase.

User-supplied requirements (proposal specifications, not benchmarked or verified final minimums):
- Development PC: Intel Core i5 / AMD Ryzen 5 or equivalent, 16 GB RAM+, 50 GB free SSD.
- Android smartphone: 64-bit quad-core+, 4 GB RAM+, 2 GB free storage plus photo space, built-in rear camera; Wi-Fi/mobile data for downloads.
- Optional Google Gemma 4 E2B local AI: approximately 2.58 GB LiteRT-LM model file; approximately 1.1 GB mobile model-weight memory; 8 GB RAM+ recommended; proposed Pixel 8 / Galaxy S23 class or equivalent.
- Proposed runtime Android 7.0+ (**verify against actual final React Native/Expo build**). Development Windows 10/11, macOS, Linux.
- Tools: VS Code; Android Studio / Java 17; Node.js 24 LTS and npm; Git, Figma.
- Mobile application: TypeScript, React Native, Expo, SQLite local storage.
- Website/update service: HTML, CSS, JavaScript, Vercel, Neon PostgreSQL.

Sample insertion order: RAD model figure → phase explanations → hardware table and explanation → software table and explanation → Activity Diagram discussion cross-referencing Appendix A (Figure A.1) → ISO 9126 evaluation explanation with six characteristics. Evaluation respondent count, questionnaire/rating scale, data gathering and statistical treatment were not confirmed; do not make them up.

Example source footnotes ¹–⁹ from the Hourly conversation were study-specific and must never be automatically pasted into a different study. Validate publication details and claims independently if reused for Hourly.