# ARC DASH
ARC created an online, interactive dashboard - DASH - to understand where we are excelling, and where we are falling short. DASH is organized according to MPO impact areas such as project, program, or regional performance. Users can navigate to a specific topic such as congestion reduction, safety, and equity, where they can read short compelling narratives, visualize trends, and delve into regional performance measures. Users can also interact with charts and maps, download data, and share findings. 

DASH is a one-stop shop for data that was previously spread across disparate sources and not widely shared. A variety of data is used to build a story around these measures, including data from the following: GDOT crash reports, LEHD, INRIX, local governments, transit operators and sketch model software, activity based model, project performance and delivery, and census data. Housing our performance data in one location gives ARC staff and its partners greater accessibility to data. Local governments and the public in particular can look to DASH to understand current and historic conditions, and create better projects in the future. Sharing this information in an approachable way helps ARC reach a broader, less technical audience while satisfying federal requirements. Visual storytelling also helps impact ARC’s regional policies and goals by tying salient data points to recommendations and actionable policy objectives. 

To build DASH in-house, ARC relied on staff’s knowledge and interest in R, GIS analyses, technical but approachable storytelling, and design. Staff was fortunate to have time to research best practices, experiment with design and functions, establish a design vision, and collaborate with other ARC staff to understand their needs. To ensure staff has the right competencies, ARC supported external technical trainings if warranted and self-guided trainings, and encouraged autonomy when building the dashboard platform. 
# Structure
## 1. Homepage
*Link:* https://atlregional.github.io/DASH/<br>
*Describtion:* Home page of ARC DASH.<br>
*Language:* Written in HTML, building the web page stucture. 1. Flexible to improve the structure and web design for a more attracting looking; 2. flexible to add, delete, modify chapters and replace current chapters by apps built by other visualization tools.<br>
*Code:* [atlantaregional/DASH/Branch: master/index.html](https://github.com/atlregional/DASH/blob/master/index.html)<br>
## 2. Regional Performance
Under **Regional Performance**, there are 9 topics designed. **Congestion Management**, **Equity** are currenly available. The ongoing part are Air Quality realted parts under **Environmental Sustainability** topic  
### 2.1 Congestion Management
*Link:* https://atlregional.github.io/DASH/Congestion_Management.html<br>
*Describtion:* Congestion Management subtopic in DASH. Showing **Bottlenecks**, **Regional Speed** in Atlanta metropolitan area, based on 2018 INRIX data. **Transit Congestion** part are under construction<br>
*Language:* HTML + R. Using R library [Shiny](https://shiny.rstudio.com/), [Leaflet](https://rstudio.github.io/DT/), [DT](https://rstudio.github.io/DT/)   <br>
*Code:* [atlantaregional/DASH/Branch: master/Congestion_Management.html](https://github.com/atlregional/DASH/blob/master/Congestion_Management.html)<br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        PLACEHOLDER Shinyapps<br>
*Learn More:* [ARC's Congestion Management Process(CMP) page](https://atlantaregional.org/transportation-mobility/roads-highways/congestion-management-process/)   
### 2.2 Equity
*Link:* https://atlregional.github.io/DASH/Equity.html<br>
*Describtion:* Equity subtopic in DASH. Providing **Map**, **Download Data** functions, **Methodology** and other information for ARC's Equity Analysis, based on 2017 American Community Survey(ACS) data.<br>
*Language:* HTML + R. Using R library [Shiny](https://shiny.rstudio.com/), [Leaflet](https://rstudio.github.io/DT/), [DT](https://rstudio.github.io/DT/)   <br>
*Code:* [atlantaregional/DASH/Branch: master/Equity.html](https://github.com/atlregional/DASH/blob/master/Equity.html)<br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        PLACEHOLDER Shinyapps<br>
*Learn More:* [ARC's Regional Equity and Inclusion page](https://atlantaregional.org/regional-equity-and-inclusion/)  
### 2.3 Environmental Sustainability
### 2.4 Freight Movement + Economic Vitality
### 2.5 Infrastructure Condition
### 2.6 Reduced Project Delivery Delays
### 2.7 Safety 
### 2.8 System Relibility
### 2.9 Transit
## 3. Program Performance
### 3.1 Livable Centers Initiatives
### 3.2 Mobility Services
### 3.3 Transportation Alternatives
## 4. Project Performance
### 4.1 RTP Project Evaluation
*Link:* https://atlregional.github.io/DASH/RTP.html<br>
*Describtion:* Regional Transportation Plan(RTP) subtopic in DASH. Providing **Map** and **Table** functions for ARC's RTP project Evaluation information, based on 2015/2040 travel demand model.<br>
*Language:* HTML + JavaScript     <br>
*Code:* [atlantaregional/DASH/Branch: master/RTP.html](https://github.com/atlregional/DASH/blob/master/RTP.html)<br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        [code need to move to ARC github](https://github.com/shichenfan/proj-eval)<br>
*Learn More:* [ARC's Regional Transportation Plan page](https://atlantaregional.org/transportation-mobility/transportation-planning/regional-transportation-plan/)
### 4.2 TIP Project Evaluation
*Link:* https://atlregional.github.io/DASH/TIP.html<br>
*Describtion:* Transportation Improvement Program(TIP) subtopic in DASH. Providing **Map** and **Table** functions for ARC's TIP project Evaluation information, based on 2015/2040 travel demand model.<br>
*Language:* HTML + JavaScript   <br>
*Code:* [atlantaregional/DASH/Branch: master/TIP.html](https://github.com/atlregional/DASH/blob/master/TIP.html)<br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        [code need to move to ARC github](https://github.com/shichenfan/qwe)<br>
*Learn More:* [ARC's Transportation Improvement Program page](https://atlantaregional.org/transportation-mobility/transportation-planning/transportation-improvement-program/)
## 5. Contact
*Link:* https://atlregional.github.io/DASH/#contact<br>
*Describtion:* Contact information for ARC stuff working on DASH program; Questions about data, methodology used on DASH or future collaboration can be contacted through email, phone or visiting ARC office; Coding issues and improvemnet suggestion are welcome to comment on our GitHub page. Thanks!<br>
*Language:* HTML<br>
*Code:* PLACEHOLDER<br>
