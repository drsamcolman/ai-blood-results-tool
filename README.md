# ai-blood-results-tool

**AI FBC Blood Results Interpretation Tool**

This project is a prototype AI tool designed to standardise the interpretation of blood results in primary care.

Variation in follow-up decisions between clinicians can lead to inconsistent care and inefficiencies. This tool aims to reduce that variation by providing structured, guideline-aligned interpretations of common blood results.

**Problem**

In GP practice, interpretation of blood results is often:
- variable between clinicians
- dependent on experience
- inconsistently aligned with local guidance

This can result in:
- inconsistent follow-up
- unnecessary repeat testing
- increased cognitive load

**Solution**

A lightweight AI tool that:
- interprets blood results using structured prompts
- aligns outputs with regional guidance
- provides consistent follow-up recommendations

How it works:
- Used no code platform AI tooling (Lovable) for structured prompting to interpret FBC results
- Applies structured clinical logic
- Outputs standardised recommendations

<img width="711" height="716" alt="image" src="https://github.com/user-attachments/assets/0137bc8d-dc13-40f5-be31-a7abfed8ed6b" />


**Iteration**

This tool was:
- tested in real GP workflows
- iterated based on clinician feedback
- refined to improve clarity and usability

Future directions
- Expansion to additional investigations
- Incorporation of patient-specific context
- Integration with EHR systems

**Case Example**

An anonymised male smoker who ultimately had lung cancer found on a Chest X-ray.

Results input:
<img width="704" height="709" alt="image" src="https://github.com/user-attachments/assets/1df56b21-51b8-402f-814a-b23be5743928" />

Interpretation: 
<img width="692" height="482" alt="image" src="https://github.com/user-attachments/assets/6d320eda-636b-4721-a938-c64e49c319f5" />

Nuance: 
This case helped me realise the need for iterating new rules for raised platelets which can be indicative of lung cancer, amongst other cancer types, inkeeping with the 'LEGO-C' initiative (lung, endometrial, gastric, oesophagus, colorectal). A Chest X-ray should be prompted, as well as further focussed symptom-based questionning. 
