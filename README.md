# VetDD Public Channels

   > Please note there is a "navigation" button on the top right of this page's header for you to navigate to the section you wish to read.

## What is VetDD?

VetDD is a veterinary disease repository designed primarily for students in the veterinary field. It provides categorised, section-by-section information on over 100 animal diseases — covering causes, clinical signs, gross pathology, pathophysiology, diagnosis, and more.

Please note: The first iteration of its release is not a final form. It is simply a delivery of the proof-of-concept (am MVP) and, enables interested members' ability to contribute to the information set in VetDD. 

This manner of deployment, interface, and the backend database hosting all the information is simply an aggregation of the various veterinary diseases and symptoms veterinians will come across in their profession. By providing this aggregated layer, the hope is to ease the complexity of navigting the fragmented nature of academia that presides the medical (& veterinary) industry today.

This Github repository is where members of the public can contribute feedback to improve the accuracy and depth of disease information displayed in the app.


## How This Repo Works

Each disease in VetDD has its own file inside the `diseases` folder above. The file is named per the disease name in all lowercase, with a hyphen instead of a space, for example:

- `diseases/botulism.md`
- `diseases/foot-and-mouth-disease.md`
- `diseases/bovine-tuberculosis.md`

Each file contains the same set of sections that appear in the app. The initial content is marked as:


`Initial: Content shown in the app is from launch`

For members wishing to submit feedback;
   1. Please check the feedback backlog that is still pending implementation **before** submitting anything. You can find this by navigating to the "Pull requests" tab above (or click [here](https://github.com/jastejsl/vetdd-feedback/pulls)).

      - If there is a pull request made on the same disease you wished to provide feedback for, please wait until that feedback has been implemented, and only after, submit your feedback.
      - If there are pull requests in the backlog queue but, it is not on the disease(s) you wished to provide feedback on, you don't need to wait. You can go ahead and submit your feedback.
     
   2. Please read the two sections below namely [How to submit feedback for existing diseases](https://github.com/jastejsl/vetdd-feedback/blob/main/README.md#how-to-submit-feedback-for-existing-diseases) and [How to add new diseases](https://github.com/jastejsl/vetdd-feedback/blob/main/README.md#how-to-add-new-diseases) before attempting to submit feedback
   3. Familiarise yourself with the [Rules for contributors](https://github.com/jastejsl/vetdd-feedback/blob/main/README.md#rules-for-contributors) section


### Tip for researchers & academics:

If you wish to be credited for your contributions outside the scope of VetDD, be sure to link your Github profile with ORCID. 

To do this, navigate to your [profile settings](https://github.com/settings/profile) → Scroll down to "ORCID iD" → [Connect your ORCID iD](https://github.com/settings/orcid_connection/new). 

More details on ORCID are avaialble here: https://info.orcid.org/what-is-orcid/ .

_Please note: How ORCID handles & reflects the correlation is outside the scope of VetDD's operations._


---


## How to submit feedback for existing diseases

Follow these steps to contribute feedback on any existing diseases:

### Step 1 — Navigate to the Disease File

In the `diseases` folder above, find the file for the disease you wish to provide feedback for.

For example, to give feedback on *Rabies*, open `diseases/rabies.md`.

### Step 2 — Add Your Feedback

First, press the pencil icon in the top right section of the header.

Under the section you want to edit, **add a new line** *below* the existing content. Do **not** remove or modify any existing lines. This is very important!

Format your feedback as follows:

**To suggest a change:**
```
Change ___ → ___ (source)
```

**To add new information:**
```
Add ___ (source)
```

**Example:**
```markdown
### Clinical Signs
Initial: Content shown in the app is initial content from launch
15 April 2026: Add ascending paralysis in cattle cases (Acha & Szyfres, Zoonoses, 3rd ed.)
16 April 2026: Change "salivation" → "hypersalivation with inability to swallow" (Source as a link)
```

Note: Citing a publicly accesibly link for the source in this feedback process is highly suggested and preferred.

When physical books/private journals are used as a source, it would be appreciated if a link to the book's/journal article's listing page and a page number is  provided.

### Step 3 — Submit the changes

Once you have made your changes to a disease page, on the page:

1. Press the `Propose changes` button.
2. In the message box, clearly indicate the sections under the diseas where edits were suggested.
    
    For example: `"Rabies – Clinical Signs"`
    
    If you have made suggestions to multiple sections in one disease, in your message, use a new line per (disease & section) to ensure clarity.
    
    Example: 
    
    `"Rabies - Clinical Signs"`
    
    `"Rabies - Pathophysiology"` 

3. Once you have listed all your edits, submit the form and press the `Create pull request` button that appears in the next popout. The message field should populate with the same information you just wrote out.

A maintainer will review your feedback, verify sources, and accept or reject the feedback.

To ensure your suggestion is promptly accepted, it is advisable to provide the sources as a publicly accesible link.

You will receive a notification in Github about the status of your feedback.


---


## How to add new diseases

If there is a disease that is not included in the `diseases` folder, please follow these steps to add it.

### Step 1 - Copy the template

Navigate to the page [`disease-template.md`](https://github.com/jastejsl/vetdd-feedback/blob/main/disease-template.md) and copy the format of the template (press the copy button in the header).

### Step 2 - Create a new page in the main folder

   - Navigate to the [`diseases` folder](https://github.com/jastejsl/vetdd-feedback/tree/main/diseases) and click "Add file" → "Create New File"
   - Label this page (at the top) with the ending `[disease].md`
       - Ensure you only use lowercase and use a hypen "-" instead of spaces
       - Ensure you add `.md` to the end of your file name
   - Paste the template text you just copied into the page section
   - Edit each section in the page as specified
   
### Step 3 - Submit the changes

Once you have made your changes to the new disease page:

1. Press the `Commit changes` button
2. There is no need to detail each section where information has been added, simply type `New Disaese added: [disease name]` as the commit message. Submit this form.
3. Press the `Create pull request` button that appears in the next popout

A maintainer will review your feedback, verify sources, and accept or reject changes.

To ensure your suggestion is promptly accepted, it is advisable to provide the sources are as a publicly accesible link.

You will receive a notification in Github about the status of your suggestion.


---


## Rules for Contributors

| Rule | Detail |
|------|--------|
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

Each disease we learn of is related to a diagnostic process to confirm it. Whether it be at post-mortem (resulting in apparent pathological signs) or during the patient's life (resulting in various clinincal signs and lab findings), the simple process of elimination is almost always a "sample in = diagnosis out". Now, combine this with the fact that multiple findings (whether clinical or pathological) can stem from multiple sources, the task simply becomes more **complicated**. Not _neccesarily_ "stratified", just "complicated" - cases where primary and secondary causes of the manifestations present _stratify_ the task of finding the diagnosis, multiple 'distractors' (all possibly "primary") simply cause for repeated runs of the formula "sample in = diagnosis out". This sort of filtering process is one that, with the aid of modern technologies, became an interest of mine to explore how to bring it to life. Result: VetDD

For the intial launch, I have utilised my own study notes made during my process of studying the various content along with various student summaries for the information fields. It is thus highly encouraged and reccomended that if there is any misinformation present, please do submit a feedback request as guided above to help improve the accuracy of the information in the app. Additionally, please do refer to the [`transparency`](https://github.com/jastejsl/vetdd-feedback/tree/main/transparency) folder above to find more information. An important note: as of the launch date (7 May 2026), the app is still in a MVP (minimal viable product)/proof of concept phase. The public awareness of it is in an effort to begin receiving feedback.

I hope it helps all of you that wish to use it and, to those that contribute to it, I sincerely thank you! :)

Over time, from the day of its launch, I will periodically update and make changes needed based on the feedback submitted and new academic findings (if brought to my attention). This is simply a "pet project" of mine to help me have a unified layer for the vast field of academia upon which the practice of medicine (including veterinary medicine) stands; whilst building the database, I realised with a quick paint job, I could easily make this a publicly accesible tool.

I hope that by sharing this creation, it helps us all become better Vets someday...

Sincerely,
Jastej :)
