## A special thanks

I would like to extend a special thanks to Gitbook for allowing VetDD’s documentation & feedback repo to be hosted under their Community Plan. 

For the neat layout & navigation of this repo, please visit the following URL: https://vetdd.org/feedback  

---

# VetDD Public Repo

This repository serves two purposes:

1. An open and ungated feedback system to process feedback for VetDD.
2. A layer whereby important documents such as the Privacy Policy and Terms of Service are hosted.

Supplementary benefits such as build logs, notes etc are secondary to the nature of this repository’s main two purposes.

---

## To submit feedback

The feedback process has been detailed in full via the Gitbook hosted page(s) here: https://vetdd.org/feedback/feedback-process/edit-existing-entries

As a summary;

1. Navigate to the file representing the entry in either `diseases` or `syndromes` 
2. Fork the repository & edit the file as per the following guidelines:
    1. **To suggest a change:**
        
        ```markdown
        Change ___ → ___ (source)
        ```
        
    2. **To add new information:**
        
        ```markdown
        Add ___ (source)
        ```
        
    3. **Example:**
        
        ```markdown
        ### Clinical Signs
        Initial: Content shown in the app is initial content from launch
        15 April 2026: Add ascending paralysis in cattle cases (Acha & Szyfres, Zoonoses, 3rd ed.)
        16 April 2026: Change "salivation" → "hypersalivation with inability to swallow" (Source as a link)
        ```
        
    
    Note: Citing a publicly accesible link for the source in this feedback process is preferred.
    
    When physical books/private journals are used as a source, it would be appreciated if a link to the book's/journal article's listing page and a page number is  provided.
    
3. Submit the feedback via a pull request
    1. The default heading is acceptable
    2. In the extended description box, clearly indicate the sections in  the entry where edits were suggested.
    For example: `Rabies – Clinical Signs` 
    3. If you have made suggestions to multiple sections in one disease, in your message, use a new line per (disease & section) to ensure clarity.
    Example:
        
        ```markdown
        Rabies - Clinical Signs
        
        Rabies - Pathophysiology"
        ```
        
    4. Create PR

---

## To create a new entry

The feedback process has been detailed in full via the Gitbook hosted page(s) here: https://vetdd.org/feedback/feedback-process/create-a-new-entry

As a summary;

1. Navigate to the folder of interest; `Diseases` or `Syndromes`; and copy their tempalte (named as either `disease-template` or `syndrome-template`)
2. Navigate to the relevant “new” files such as new-disease-entry or new-syndrome-entry
    1. Rename the file according to the following speifications: `/user-generated/[name].md]` 
    2. Paste the template contents into the file contents section
    3. Edit the template as needed to adequately cover the various information sectioons
3. Submit commit 
    1. Simply have “Add [Disease/Syndome] [name]” as the commit heading
    2. No message needed

---

## Rules for contributers

| Rule | Detail |
| --- | --- |
| **Review ongoing feedback first** | Before creating a feedback submission, navigate to the "Pull requests" tab above to view ongoing feedback. Do not submit feedback for a disesae that may have a feedback backlog item pending review. |
| **Never remove previous lines** | All previous feedback lines must be preserved. Only add new lines below existing ones. |
| **Always date your line** | Use the format `DD Month YYYY:` at the start of every feedback line (e.g. `15 April 2026:`). |
| **Always include a source** | Every feedback line must reference a credible source in parentheses at the end — e.g. a textbook, journal article, or official guideline. Links are preferred to expedite verifiability. |
| **Be specific in each feedback point** | Use `Change ___ → ___` for corrections and `Add ___` for new information. Avoid vague comments/long sentences. |
| **Be specific in in the form message** | The commit message helps act as a traceability point for the suggestion being made whilst the pull request message helps the maintainer of the app promptly review your suggestions. Please do add both. |

Your contribution directly improves what veterinary students and professionals see in the app and we thank you for your contribution.

---

## A word from the creator

To all those reading, I sincerely thank you for taking the time to read until the end of this document. From hereon out, I will speak from the heart, as I would to you if we were to speak in person.

VetDD is the birthchild of my imagination stemming from the discontent I harboured when studying the content presented to you in the app. The fragmented nature of "modules", and the lack of apparent relationships during the learning process is one that frustrated me. Having envisioned the simplicity of the end result needed to unify these fragments, I set out to build what you see today.

Each disease we learn of is related to a diagnostic process to confirm it. Whether it be at post-mortem (resulting in apparent pathological signs) or during the patient's life (resulting in various clinincal signs and lab findings), the simple process of elimination is almost always a "sample in = diagnosis out". Now, combine this with the fact that multiple findings (whether clinical or pathological) can stem from multiple sources, the task simply becomes more **complicated**. Not *neccesarily* "stratified", just "complicated" - cases where primary and secondary causes of the manifestations present *stratify* the task of finding the diagnosis, multiple 'distractors' (all possibly "primary") simply cause for repeated runs of the formula "sample in = diagnosis out". This sort of filtering process is one that, with the aid of modern technologies, became an interest of mine to explore how to bring it to life. Result: VetDD

For the intial launch, I have utilised my own study notes made during my process of studying the various content along with various student summaries for the information fields. It is thus highly encouraged and reccomended that if there is any misinformation present, please do submit a feedback request as guided above to help improve the accuracy of the information in the app. Additionally, please do refer to the `transparency` folder above to find more information. An important note: as of the launch date (7 May 2026), the app is still in a MVP (minimal viable product)/proof of concept phase. The public awareness of it is in an effort to begin receiving feedback.

I hope it helps all of you that wish to use it and, to those that contribute to it, I sincerely thank you! :)

Over time, from the day of its launch, I will periodically update and make changes needed based on the feedback submitted and new academic findings (if brought to my attention). This is simply a "pet project" of mine to help me have a unified layer for the vast field of academia upon which the practice of medicine (including veterinary medicine) stands; whilst building the database, I realised with a quick paint job, I could easily make this a publicly accesible tool.

I hope that by sharing this creation, it helps us all become better Vets someday...

Sincerely,

Jastej :)
