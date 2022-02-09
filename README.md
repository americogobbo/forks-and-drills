# Brushes for Gimp 2.10

## Set made to 2.10 version release
This set contains parametric and rasters (.gbr and .gih) brushes thought to first 2.10 GIMP release.

Motivations/Scopes of my GIMP 2.10 Brush Set
--
I have been working in the last 10 years on GIMP and my preoccupation and efforts are focused on brush design.
Since 2011 I am collaborating with other artists to understand how is possible to improve the painting performing on GIMP through brushes and after GIMP 2.8 studying the paint dynamics.
I have written some articles about these topics in past and if someone is interested to know a bit more about the background of current ideas about the future brush set is possible to read here: https://medium.com/graphic-arts-free-software/tagged/gimp

![Testing of raster .gih brush](https://github.com/americogobbo/forks-and-drills/blob/GIMP-2.10-brushes/method-workshop-brush.png)

Criteria to organize the GIMP 2.10 Brush Set
---
I have thought and commented on some of my ideas and concepts about brush design on GIMP during the last LGM a Rio with Han Ahryeom, Jehan Pagés and João Bueno, the points that follow are some of my conclusions and I am trying to use this to future brush set of GIMP 2.10:

* The brushes need to have good sharpness within… is impossible to increase this quality… only lost it.
* To have a median stain opacity over 70%… if you need a soft brush is easy to control this in the Tool Options settings or with Paint Dynamics.
* To have a good stain quality with a ‘comfortable’ dimension is important to brush scaling during painting sessions. I have thought the standardization for the sizes: 64, 128, 256 and 512 pixels, each dimension is thought for a kind task, e.g., 64 pixels for the pen, pencils, crayon, colour pencils, etc … 
* To improve or suggest the use of parametric brushes as some classic brushes, mainly round and flat kinds. Is possible to increase the performance using parametric brushes with specific paint dynamics.
* To promote also an equilibrium between the two kinds of raster brushes, the .gbr, and .gih formats.
* To select static stains as .gbr capable to resolve or to mimic efficiently brushstrokes utilizing the default spacing or greater (default is 10%).
* To select animated brushes, the .gih, with good and well-formed brushstrokes using the default spacing or greater (default is 20).
* To identify the kind of stains more adequate to different scopes (based on the criteria of the last point), for instance, and mainly on paint or drawing, to generic effects or faux effects to mimic some textures of nature or material or yet to decorative or ornament scopes. In this way, is possible to help the user identify the possibilities and usage of each stain.
Brushes based on generic stains are very ductile but also very metamorphic with tool options settings and paint dynamics curves. In theory, any kind of stain is possible to use to paint, to draw, like stamping, like texture or decorative scopes. This flexibility sometimes can be a problem or a limitation, mainly if the user does not know as these skills could or might be used on digital painting.    
* To reorganize more specifically the brushes for scopes and families, (e.g., draw, paint,..., pencil, crayon, pen).
* To organize the sets on different folders thought for permanent tags. To think of a new tag named ‘Default’ to filter the gimp default set of others installed by a user.
* To organize a normative to call the assets in general. The scope has good ways to sort and identify each asset (with an ID unique followed by a name with a progressive number and a general scope of the asset).
    
To justify many of these criteria, exposed above, were made many tests around spacing, hardness and other issues on dynamics related to brushes. But, in general, the spacing is the more critical factor to painting performing, if we have the default spacing to the brushes is possible to improve the performance of the painting (more comfortable and agile).

During all processes of the creation of the new set I have discussed with many artists: Mozart Couto, Gustavo Deveze, Aryeom Han, Elias da Silva.
I have published all my in progress on my g+ account with many posts shared on GIMP official channels. My impression was that the paths are correct and always harmonized with the feelings of many users and tastes :-)
Also, I have published a post on Pixls.us to discuss the choices around *real brushes* that also help me define better what to do concerning the default set defining the additional sets as *Extras* and *Jag* (my vision around real brushes).

Finally, is obvious that choosing or organizing with these criteria the brushes we have not only an increase in performance but also, a better knowledge of how is possible to use the stains as brushes. In short, introduce/define new approaches to how the brushes or stains could be used in a fast and creative way on GIMP.
    
Brushes to paint and tools to draw
---

Is possible to deduce that we have essentially two kinds of *brushes*... those based on the generic stains that have some properties of real brushes when they are configured in precise conditions and settings... and others based on real brushes as is, in general, the parametric or raster brushes based in simple shapes and without exotic effects. So, is interesting to improve the usage of the second type, of the real brushes on GIMP. In this sense, I have prepared some concepts of **real brushes** that can emulate reasonable the bristle quality with a good compromise with the current features of GIMP.
With these brushes is possible to paint in a similar way to real brush with different techniques supported by good and specific paint dynamics, tool presets, or based on user knows how to use the tool options settings with specific or not paint dynamics (in some cases and with limitations, obviously).
The real brushes concept on GIMP actually can be resolved with all kinds of brush formats, like round, flat, filbert, liner, etc... but ideally with rasters brushes and specifically with the .gih. In general, the brushes are used to paint but is possible to use them to other scopes such as calligraphy or also to the drawing, for instance, with washed inking technique.
I have thought to add some *brushes* to draw (pencil, colour pencil, charcoal, pastel/crayon, pen, etc)... they are not brushes really but are tools to draw... the categorization is good to help the users select more easily the tools to these tasks.

Generic Stains
---
The generic stains that are not possible to use as *brush*, following the _Criteria to organize the GIMP 2.10 Brush Set_ will be considered as generic *effects* and classified along with nature, dirt, grunge, spatter, etc.
The idea to categorize the stains in this way is only to simplify and help the user understand which are the stain categories easier to use to mimic the classic aspects of painting on digital, but, is clear that each mark could or might be used with different ideas, scopes and methods... but this must be made with proficiency and mastering and not all are prepared to have this vision or skills... so, the categorization is a path to give more indications how is possible to use the stains in another way.
Recently I have discussed this with Vasco Alexander and this is an excerpt of our correspondence that I think clarifies a bit my issue about generic stains and usage difficulties around painting on digital:

> _Brushes based on generic stains are like the pencils of the digital art world. They are available everywhere, everyone has some experience using them and of course, one can make beautiful drawings with them. It might be also true that not much more is needed for learning. But, because of our predetermination of thinking how a pencil has to be used, it is hard to break out of this habit and to develop a broad spectrum of own marks._

> _I think with generic brushes, especially the most commonly used hard round brush, it is very much the same thing. In my eyes, there is a misconception in digital painting that is not grounded in the tools, but in the teaching.
I can't say how often I heard something like: The hard round brush is all you need or I do 95% of my work with a hard round brush. It's almost like an unwritten rule. But of course, artistic development needs diversity._

> _On the other side of the extreme, some people install 1000 brushes and never get along with one of them - in the end, fall back to the default brushes and eventually start following you need only one brush thing._

> _As someone who made brush sets, I tried to think about the selection of tools to be included in an art supply store - demand, quality, variety. The decision, what to use, has to be made by the customer, artists and teachers, not by me. I think, that this is even more evident when we talk about the creation of defaults for an app. We have to take a step back from our own opinions and preferences and provide the highest quality, but taking the demands of the users into account. For sure this is no easy task."_

To know better what is possible to use is much important to improve the painting experience/performing and not only think that we need more and more features... and mainly we must think that many of discussions about improvement could be related to insufficient info about how to use the tools and basic knowledge about the tools to painting/drawing on digital.

Brush Set Categorization, Naming, and Tagging
---
To organize the future 2.10 GIMP release and future pre-releases along I have thought of a specific organization of folders (as automatic tags) for the brush set.
The idea is to become more easy and usable brushes through tags to specify brush type, for that is more usable. So, in this manner will be possible, for instance, to select all round brushes to paint or to draw.
Each brush will have an ID unique to become easier the sort and avoid confusion with exotic names or without any rule or criteria.
It was recovered and rethought the previous classification and names with some changes and improvements, Basic, Media (now called 'Medium') and Textures (now called 'Effects') yet are present but with some variations on the previous concepts.

The organization proposed is:

*Basic* - contains 3 folders dedicated to this category, B0, B1, and B2.
The **BO** folder contains the .vbr basic brushes, round and block (hard and soft versions). They are the Classic brushes that the user to any task to painting or drawing. The idea to put in evidence these brushes are motived for my ideas and concepts around the real possibilities of parametric brushes on GIMP with paint dynamics to solve many issues of pictorial techniques for the traditional digital painting based in the current mainstream and tastes around finishing of the works.
Another idea is to promote the .vbr and his editor a the rule more effective for the concept artists and not only.
My set could appear a bit large, but I have verified with my friends and artists that are generally accustomed pick the variation brushes directly from the brush palette instead to customize them via his editor... probably this is a gap in our documentation or we need to write tutorials about how effectively to use all instances around the brush on GIMP.
The **B1** folder contains some versions of concept brushes dedicated to emulating the 'real brushes' or brushes with bristles.
The **B2** folder contains the essential set to dry media (pencil, charcoal, chalk) and a new version of the hatch pen.

**Effects** - contains raster brushes thought to make texture effects in general. I have thought that the term 'effects' is more general and could be used also to aggregate brushes based on rasters images dedicated to faux or other exotic effects.

**Medium** - is the attempt to conserve the previous and *media* term classification with some interesting stain brushes (static and dynamics). The criteria for the stains and how we are building this set was modified in function of something more near of real behaviour of brushes and tools to draw/paint. In this set, we have some brushes that can emulate some media or techniques but in general, the settings on tool options need to be more specific... because the generic stains to emulate techniques are much dependent on how are configured our settings on Tool Options.

**Smudge** - with the new features of the smudge tool I have thought it necessary to create a set specific to use with this tool, normally we can use any brush, but talking with an artist as Mozart Couto, Elias da Silva and Gustavo Deveze, I have discovered that each artist has brushes more specific for this usage. So, I have identified the modal behaviour of these brushes and I selected brushes of the previous set and some new to this scope.

The **Legacy** category now is added in a separate category called 'Extras' to implement the default series. In my opinion, the 'Extras' concept is more adequated to solve not only 'legacy' but other additional brushes to complement in future the default pack when the artists are interested or when they think necessary.
I think it is useful to create a GitHub account to solve this set.

To order the brushes on the natural GIMP lists in the system file manager I have adopted a coded alphanumeric. An example the Media stain brushes will be organized:

    **ID    |   Folder   |   Tag1   |   Tag2   |   Alias Name on GIMP Lists   |   Name of archive on file manager**
      M1.      Medium       Paint        
      M1.01    Medium       Paint      Round      M1.01 Oil. Viscous O1          m1.01-oil-viscous-01.gbr
      M1.02    Medium       Paint      Round      M1.02 Oil. Viscous 02          m1.02-oil-viscous-02.gbr
      M1.03    Medium       Paint      Round      M1.03 Oil. Viscous 03          m2.03-oil-viscous-03.gbr
      M1.04    Medium       Paint      Round      M1.04 Bristle.                 m1.04-bristle.gbr
      M2.05    Medium       Paint      Effect     M1.05 Acryl. Bristle           m1.05-acryl-bristle.gih

Alias Name is formed by = [ID] + [*Alias Name* '.' (dot) to .gbr or .vbr brushes and '+' to the .gih brushes].
For instance: 'M1.04 Bristle. 04

The *Alias Name* and *Archive Name* follow the same schema with a difference that the archive has *Folder* name, for instance, the named archive of the last example is: 'm1.04-medium-charcoal-01.gbr'. This schema is adopted because on the file manager is not possible to have the tag feature :-).

The 'tags' of the brushes are formed by 'Folder Category' as folder tag, 'Tag1' and 'Tag2' as normal tags, directly saved on the Tags.xml GIMP system archive.

The reasons to adopt this codification are many: is easier to administrate the brushes, is easier to identify univocally the brush, is easier to design brushes and verify them during the process.
Ideally, we must think of a categorization more transparent or hidden for the assets on GIMP... and not only based on the alphabetic ordering. Is natural for all users to have criteria more personal, like as favourites... if we think a spreadsheet is possible to have also ordered things based on our tastes and needs. At this moment is not possible to have this feature and I have thought of a way to solve this in the GIMP default set and also a manner to harmonize the future additional sets of other authors.
In my opinion, is necessary to have an order on the default GIMP set, this is a good way also to exemplify how is possible to collect and organize assets efficiently. This is not a rule for all users, but I think that GIMP must have rules to organize their default assets. The users could be adopted or not these rules as is more natural to them.

Brush Asset Authors Reference
---
Yet is not possible to add info about the author and license of each brush, but I have thought that is a good idea, at this moment, to add this info directly to the layer of the brush. Therefore each brush set of the GIMP 2.10 will be rewritten adding the info of authors in their brushes, in my opinion, this avoids the necessity of a document with reference of authors to each brush. Until this moment the authors of the brush set are:

* David Revoy
* Elle Stone
* GIMP (when was not possible to identify the original author).
* Gustavo Deveze
* Jag (Americo Gobbo)
* Johannes Engelhardt
* Justin W (Akisu-sama)
* L'ubomir Zabadal
* Mathias Jonathan
* Mozart Couto
* Ramon Miranda
* Rene Jensen
* Ulf Worsoe
* Vallie (valliegurl)
* Vasco Alexander

License: GPL 3.0
