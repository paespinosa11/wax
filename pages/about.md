---
layout: page
title: What is Wax?
permalink: /about/
---

Lorem *ipsum dolor* amet organic etsy tumblr vaporware twee bespoke chambray chartreuse hammock synth man braid fashion axe. Pickled chia mlkshk, [food truck](https://hipsum.co/?paras=5&type=hipster-centric&start-with-lorem=1) hot chicken cloud bread typewriter microdosing banh mi.[^1] Readymade shabby chic echo park, brunch cornhole mumblecore brooklyn fixie chillwave dreamcatcher tofu bicycle rights. Banh mi skateboard gochujang, irony pabst pop-up leggings disrupt swag banjo deep v mlkshk food truck. Enamel pin mixtape pug venmo raclette lo-fi bitters banh mi letterpress 90's chillwave schlitz prism umami bushwick. Ennui scenester try-hard, poutine tousled occupy godard gentrify glossier locavore copper mug kogi irony poke biodiesel.

Snackwave freegan brooklyn crucifix raw denim master cleanse austin. Fanny pack PBR&B four loko meggings slow-carb knausgaard. Schlitz occupy shaman selvage fixie leggings.[^3] Cliche waistcoat sriracha chia, raclette salvia aesthetic man bun air plant blue bottle chartreuse.

[^1]: This is the content of this footnote.Bananas.

Art party man bun yuccie poke literally 90's irony beard cred skateboard thundercats organic snackwave food truck disrupt. Messenger bag direct trade disrupt yuccie iceland activated charcoal tumeric 3 wolf moon. Fingerstache kitsch leggings, ennui readymade celiac thundercats cold-pressed chia master cleanse lomo green juice direct trade. Raw denim put a bird on it before they sold out health goth leggings trust fund post-ironic enamel pin.

Oh. You need a little dummy text for your mockup? How quaint.

[^3]: This one is mangoes.

**Wax helps you create digital exhibits.**   
A digital exhibit is a collection of curated cultural artifacts—manuscripts, paintings, photographs, sculptures, etc—often accompanied by an explicit narrative or argument. Though Wax focuses on images and text, it could be used for sound or video collections with some customization.

**Wax is an extensible workflow based on minimal computing principles.**  
Wax is hyper-aware of differences in resources, control and access around the world and close to home. As a result, it is purposefully lightweight: a few Ruby gems, some customizable UI components, good documentation and (hopefully soon!) recipes for creating, deploying, and maintaining custom digital exhibitions.

**The exhibition sites created by Wax are static.**  
This means they consist of flat HTML, CSS, and JavaScript files that don't need to communicate in a complex way back to a server. This makes them cheaper, safer, and generally easier to maintain.

**The skills needed to create Wax sites are agnostic.**  
This means they are largely transferable for use in other digital projects. 'Learning Wax' does not mean learning how to use a platform. It involves learning the fundamentals of web development, data management, and [plain text editing](https://zapier.com/blog/beginner-ultimate-guide-markdown/) while leveraging a few great open source libraries and frameworks along the way.

**Wax keeps the collection presentation separate from the collection data.**  
The Wax workflow starts with making standardized image files and metadata records and builds around them, handling canonical information, scholarly content, and site styling differently and deliberately. This makes it easier for you or others to share, reuse and reimagine your collection data in other contexts.

## Who is Wax for?

Wax was created for individuals and groups who either don't have or don't want to use a lot of resources to create their scholarly or cultural exhibits. It's best suited for folks who are willing to take on some technical responsibility in exchange for a lot of flexibility.

For beginners, Wax has a relatively high, but general-purpose learning curve. To get the most out of Wax, you should have some familiarity with:

- Using an interactive shell (e.g., Bash/Terminal) to install and interact with programs, files, and directories on your local computer.
- Using Git and GitHub to version control and collaborate on projects.
- Using Jekyll to generate static sites.
- Creating and normalizing data files (e.g., CSV, JSON, YAML)
- Using file-naming conventions and best practices.
- Editing HTML, CSS, and some JavaScript.

**However, Wax is also great for teaching or learning the skills above!** For examples of digital pedagogy via the creation of Wax exhibitions, check out [this workshop](https://www.columbia.edu/content/events/introduction-minimal-computing-humanities-building-exhibit-primary-sources-using-wax), [this GitHub repository](https://github.com/stylerevolution/stylerevolution.github.io), and [this custom Wax site](https://stylerevolution.github.io/).

**Wax is also phenomenal for professionals who play a facilitating role**, such as Digital Scholarship Librarians or Coordinators. With some practice, Wax substantially reduces the time to production and post-production maintenance costs for you and your team. In the most common scenario, students, faculty, colleagues or any other collaborators just have to provide you with a properly formatted spreadsheet and the text for the exhibits. The extras are up to you.


## So what does the Wax workflow *look like?*

Below is a diagram to give you a zoomed-out view. In summary, you create a file of metadata records for your collection (in CSV, YAML, or JSON format), organize your collection image files, and put both in the Jekyll site folder. After updating your configuration, you run a few command line tasks to prepare the data and metadata for use by the Jekyll site. Jekyll then uses special layouts and Wax components to build the exhibit and spits them out as static pages ready to publish.

From there, you can run tests on your site to catch errors and decide where and how to put it online or in offline media.

<a href="{{ '/img/wax_workflow.jpg' | absolute_url }}">
  <img src="{{ '/img/wax_workflow.jpg' | absolute_url }}"/>
</a>
