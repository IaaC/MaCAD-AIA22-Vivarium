# MaCAD-AIA22-Vivarium
![WhatsApp Image 2022-07-26 at 11 05 34 PM](https://user-images.githubusercontent.com/91753032/181112557-56e53ce2-a155-44ff-b76f-2f96e03f144e.jpeg)

OVERVIEW
In our fast-paced society, social trends and urban realities change quicker every day. People come and go and it is challenging to keep track of the evolution a city is going through. Traditional urban metrics have the ability to build urban predictions over historically gathered data. While this method is stable and reliable, data gathering takes time and cannot take everyone into consideration, lacking in depth and accuracy. Once an issue is identified, it might be too late and have escalated. Vienna’s Vivarium proposes a new way to analyse urban life, merging well-developed and proven traditional urban indicators with available online data shared by citizens, adding a new layer that allows a more holistic understanding of urban life. 

FRAMEWORK
The project studies Vienna’s existing squares and their ability to bring people together. It considers their surroundings and the activities in their proximity, to extract meaningful programs that can improve the neighbourhood without distorting what is already happening in them.

![WhatsApp Image 2022-07-26 at 11 05 42 PM](https://user-images.githubusercontent.com/91753032/181112586-26b461b8-a5ca-4ed6-9c71-42d6efa9399a.jpeg)

As a first step, the squares are located thanks to publicly available GIS information. To characterise them, their surroundings are analysed within a 500m radius. The demographic and programmatic information extracted is then used to cluster the plazas, using k-mean machine learning and agglomerative clusters, attending to different key indicators. This first process gives an overview of the need of each of the squares’ neighbourhoods and a broad idea of what the proposed program for that plaza could be.

![aia-studio_viennas-vivarium-3-730x411](https://user-images.githubusercontent.com/91753032/181112913-af8ff741-a3f9-4b4d-9634-4c09b3f4f5c4.png)
![aia-studio_viennas-vivarium-2-730x411](https://user-images.githubusercontent.com/91753032/181112919-d41eedfc-ed33-456c-9f89-80605ac47312.png)
![aia-studio_viennas-vivarium-4-730x411](https://user-images.githubusercontent.com/91753032/181112920-c18a852f-4cb7-409a-b707-6c94db8e88c0.png)
![aia-studio_viennas-vivarium-5-730x411](https://user-images.githubusercontent.com/91753032/181112983-4524c3eb-124e-4ee4-9dc9-71e54f72bb20.png)
![aia-studio_viennas-vivarium-6-730x411](https://user-images.githubusercontent.com/91753032/181113001-ab18fb6e-4b70-4a84-b388-3ea427269564.png)
![aia-studio_viennas-vivarium-7-730x411](https://user-images.githubusercontent.com/91753032/181113034-f4e1e49f-14fd-4855-a2af-3c819fce0412.png)

The second step analyses the social feeling towards the targeted square. It is done in two ways. First, doing an Instagram image analysis and, second, via a Twitter sentiment analysis. DISCLAIMER : the team understands the bias of exclusively picking social media as data source for social activities . This procedure leaves out a considerable number social groups. In future developments this will be solved. Understand the following part as a proof of concept .As mentioned, the images were extracted from Instagram due to their relatively easy access and variety. With the help of geotags, images from the targeted public spaces were grouped. In order to properly analyse complex urban images, they are cropped into scenes using the YOLO (You Only Look Once) algorithm. This increases the accuracy for the next analysis where the OpenPose algorithm is used to estimate the differnet poses and activities of the people in the images.

![aia-studio_viennas-vivarium-9-730x411](https://user-images.githubusercontent.com/91753032/181113200-bfe9787d-672f-47ff-ba45-cfb3b8aaef15.png)
![aia-studio_viennas-vivarium-10-730x411](https://user-images.githubusercontent.com/91753032/181113208-f5ab465b-39cc-48a2-82dd-9cfba1b796ab.png)
![aia-studio_viennas-vivarium-11-730x411](https://user-images.githubusercontent.com/91753032/181113238-441f1aa4-5c38-4d4f-9f93-c3f8fb14485d.png)

Afterwards, the data is combined to extract the most common activities and poses on each square and a variety an “activeness” indicator to showcase how many activities are carried out and how much movement they imply (jogging or cycling vs. sitting at a café).

![aia-studio_viennas-vivarium-12-730x411](https://user-images.githubusercontent.com/91753032/181113373-19b55df7-0d03-48f2-a0eb-453e608ad3c5.png)
![aia-studio_viennas-vivarium-13-730x411](https://user-images.githubusercontent.com/91753032/181113388-0348dbeb-05a5-470b-bb3b-35e8be14c9bc.png)
![aia-studio_viennas-vivarium-14-730x411](https://user-images.githubusercontent.com/91753032/181113399-b27ea6ee-ff1c-4a8e-91cf-b3c8919d95b8.png)

For the Twitter sentiment analysis, geo-tagged tweets give an idea of the feelings the people have towards the targeted squares and how the programs should try to improve how people conceive public space.

![aia-studio_viennas-vivarium-15-730x411](https://user-images.githubusercontent.com/91753032/181113506-267b368e-5e95-46c1-b71d-1c59ac3914a6.png)

In the end, this second part of the work flow will give the urban designer a deeper understanding on what types of programs to propose.We believe Vienna’s Vivarium can be a design aid tool to set the pace for a new way of urban policy making that takes into consideration the community’s needs and tastes.

![WhatsApp Image 2022-07-26 at 11 05 14 PM](https://user-images.githubusercontent.com/91753032/181112599-bcebb7f8-af8f-43a7-aca3-c2b41029c810.jpeg)
![aia-studio_viennas-vivarium-19-730x411](https://user-images.githubusercontent.com/91753032/181113637-022a5234-6c26-4d85-a201-064cf2322acf.png)
![aia-studio_viennas-vivarium-20-730x411](https://user-images.githubusercontent.com/91753032/181113659-e32ebcc0-0e77-4be9-b529-bf51767c6352.png)
![aia-studio_viennas-vivarium-21-730x411](https://user-images.githubusercontent.com/91753032/181113675-38f7edf9-f823-4e4a-9983-66186453b906.png)
![aia-studio_viennas-vivarium-22-730x411](https://user-images.githubusercontent.com/91753032/181113686-b8e0b159-78f2-4805-b549-c0c0ce16d5fd.png)

CREDITS
Vienna’s Vivarium is a project of IAAC, Institute for Advanced Architecture of Catalonia developed at Masters in Advanced Computation and Design (MaCAD) in 2021/2022 by students: Pablo Antuña Molina // Irene Martin // Faezeh Pakravan Noghabi // Pablo Jaramillo and Faculty: Angelos Chronis //  Aleksandra Jastrzębska // Nariddh Khean // Serjoscha Duering
