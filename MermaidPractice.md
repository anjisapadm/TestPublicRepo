```mermaid
flowchart TB
    mmflrounded["<span style="padding-left: 8px; padding-right: 8px;">Indicate the study type that resulted in your data (i.e., how the data was obtained).</span><br>"] -- Other study type or non-study data --> n1["<p style="">Being a participant in the study or a data subject could have affected participants' behavior.</p><p style="">For instance, participants might not tell the truth or omit things. This could be the case when they don't remember, focus on positive result, or give an answer they believe the researcher is looking for.</p>"]
    mmflrounded -- Randomized Controlled Trial --> n2["Data collection was blinded for participants (i.e. study participants did not know which group they had been assigned to)."]
    n2 -- Yes --> n3["Data collection was double-blinded (i.e. study participants and researchers did not know which group study participants had been assigned to)."]
    n1 -- No --> n4["Interviewers or data collectors could give different weight to elements that confirm their beliefs or that disprove them<span style="background-color: rgb(242, 71, 38);">.</span><br>"]
