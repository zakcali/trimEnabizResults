# trimEnabizResults
e-nabız is software by Sağlık Bakanlığı. I need space from  pasted laboratory results to patient's history. So I wrote a javascript program to shorten the laboratory result texts, following:
```
	25.03.2022 02:57	Üre (Serum/Plazma)	33		6 - 26	
	25.03.2022 02:57	Potasyum (Serum/Plazma)	2,7		3,5 - 5,2	
	25.03.2022 02:57	Kreatinin (Serum/Plazma)	1,32		0,70 - 1,30	
	25.03.2022 02:57	Glomerüler Filtrasyon Hızı (CKD - EPI)	60		> 60
```

as:
```
Üre:33 K:2,7 Kre:1,32 GFR:60 
```

I wrote a html web page, with minimal JavaScript coding. Just paste laboratory results text to form on the top, click "Kısalt" button, see trimmed text in the form on the bottom. Now you can select the trimmed text, and copy it to clipboard, then paste it to patients history in your EHR software
