Category: Forensics

Challenge Description: My professor told me I might find something useful in these slides

Challenge Solution: Here we're given pdf file with slides. But in fact, I don't know if I'm able to upload it to my git (I'll ask soon if it is ok). We have a lecture with slides about forensics, nothing special in slides and nothing that looks like a flag. But we can transform it to text and scan for a flag using next commands:

pdftotext Lecture_22__Forensics.pdf output.txt
cat output.txt| grep wsc

Result: wsc{y0u_c4nT_$ee_m3}, that is our flag

Flag: wsc{y0u_c4nT_$ee_m3}
