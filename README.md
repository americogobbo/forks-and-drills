# Brushes for Gimp 2.10

## Set made to 2.10 version release
This set contains parametric and rasters (.gbr and .gih) brushes thought to first 2.10 GIMP release.

Motivations/Scopes of my GIMP 2.10 Brush Set
--
I have been working in the last 10 years on GIMP and my preoccupation and efforts are focused on brush design.
Since 2011 I am collaborating with other artists to understand how is possible to improve the painting performing on GIMP through brushes and after GIMP 2.8 studying the paint dynamics.
I have written some articles about these topics in past and if someone is interested to know a bit more about the background of current ideas about the future brush set is possible to read here: https://medium.com/graphic-arts-free-software/tagged/gimp

![Testing of raster .gih brush](https://github.com/americogobbo/forks-and-drills/blob/GIMP-2.10-brushes/method-workshop-brush.png)

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
