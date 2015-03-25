# Tija
Information Technology Jobs Analyser for the Bulgarian Job Market

# Идеята
Web Crawler, който да събира информацията от българските сайтове за работа и да създава четими и полезни данни от нея, като например трендове какво се търси като знания и умения от фирмите, кои са най-популярните обяви, колко обяви са публикувани днес с линкове и прочие.

Името "Tija" произлиза от абревиатурата на "Information Technology Jobs Analyzer" с малко разместване.

# Източници
Българските сайтове за работа в ИТ сектора като:

## Портали
* http://jobs.bg
* http://rabota.bg
* http://www.jobtiger.bg
* http://www.jobspartner.bg
* http://www.buljobs.bg
* http://jobspace.bg
* https://ec.europa.eu/eures/main.jsp?acro=job&catId=482&parentCategory=482&lang=bg&pageCode=find_a_job&app=3.3.1p2-build-1
* http://www.zaplata.bg/
* http://www.mycv.bg/
* http://probook.bg/jobs
* http://www.az.government.bg/
* http://www.mediajobs.bg/
* http://www.djobs.bg/
* http://www.karieri.bg/
* http://www.talant.bg/
* http://econ.bg/%D0%9E%D0%B1%D1%8F%D0%B2%D0%B8-%D0%B7%D0%B0-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0_l.anl_t.2.html

## Специализирани

* http://workabroad.bg/
* http://www.itjobs.bg/
* http://mytech.bg/rabota
* http://www.touristjob.com/
* http://www.инженер.bg/jobs
* http://www.flexjob.bg/

## Обяви
* http://olx.bg/rabota/informatsionni-tehnologii-c610/
* http://vsi4ko.ibox.bg/section/id_7/
* http://www.ad-bg.net/readAds.php?Rub=Rab
* http://www.bitak.net/obiavi/cid/398
* http://www.obiavite.eu/?view=ads&amp;catid=27&amp;cityid=2&amp;lang=bul
* http://burkan.info/sections/Rabota%2115.html
* http://rabota.mamche.com/
* http://www.oferti.bg/?com=offers&amp;op=list&amp;sec=8
* http://www.obiavi.bg/Default.aspx?id=36
* http://www.alo.bg/obiavi/rabota/rabota-v-stranata-predlaga/
* http://www.bulborsa.com/project/viewcategory.php?cid=5


# Реализация
Системата ще се състои от три основни компонента:
1. Crawler - бот, който да обикаля сайтовете с обяви.
2. Prezentation layer - Уеб сайт, който динамично предоставя информацията от сайтовете за обяви.
3. Database (MySQL) - съдържаща информацията, която бота събира и презентационния слой показва. 

За реализацията на първите два компонента се колебая между PHP и Python + Curl. 

