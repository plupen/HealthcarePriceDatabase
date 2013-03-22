HealthcarePriceDatabase
=======================

Proposal and launchpad for an INTERNATIONAL price database to better inform healthcare consumers

Having read Ezra Klein's reprinted blog post (http://www.washingtonpost.com/blogs/wonkblog/post/why-an-mri-costs-1080-in-america-and-280-in-france/2011/08/25/gIQAVHztoR_blog.html) I believe it's worthwhile to crowdsource a freely accessible database of pricelists that spans national boundaries. Prices for every imaginable procedure, test and treatment, along with relevant travel information! Breakdowns of likely operating costs, for added insight into margins.

This is not simple. A napkin sketch of linked tables in a massive SQL-type database quickly spiralled out of control. And that is simply creating a place for all these pieces of information. Additionally, these prices would need to be continually updated, and I have some ideas about how to start that, but there is a galaxy of room to start. The ultimate goal is to create an environment where healthcare providers will actually offer the information freely, even pushing the data to this, or a more viable, web-database as a part of their marketing.

This is not easy. Most of the hurdles rely on tasks that are beyond my limited abilities (which is why github is the perfect place to start -- a thriving community of professionals!). Not to mention the logistics of eventually hosting and scaling, completing and verifying this essentially global effort.

There are sites that attempt to present a "fair price" for procedures (e.g.: http://www.healthcarebluebook.com) but most invariably suffer from a lack of transparency. What good is a number of this importance when you have no data on its origin or constitution? A single number form-factor is one solution to the problem of how to represent the mountains of data that would accumulate in an effort like this. But when something bad happens to your health, you're probably not worried about getting your hands dirty with some data. I'm also of the opinion that averages and statistics can be road-signs, but should not be your ultimate destination.

This is not my job. I don't want to make money doing this, but I would like to use this tool one day! Wouldn't you?

So consider this an opening salvo, with three main areas:

1. Construction
  a) Defining the classification of the data (Doctor, provider, price, type of price [e.g. quote or actual charge], date of price, etc)
	b) Creating a durable, efficient database structure, and the tools for updating it
	c) Creating the two main prongs of the web interface -- data entry and data queries
	d) A viable, scalable, low-or-no-cost hosting situation with robust security and backup features
2. Collection
	a) Volunteer price data collection -- cold calls to healthcare providers in your geographic area. 
	b) User-submitted bills. How about the best app or gui to smudge out your personal identifying info on actual bills? Or a web-form that can handle the traffic, that doesn't seem like it's mining your personal info?
	c) etc. There are myriad ways to do this. Let's get the best of all of them.
	d) Methods of cross-referencing, verifying and generally keeping data from corrupting before they are queryable.
	e) A sidebar: Delving into operating costs for machinery, constitution of tests, 
3. Branding and Partnership
	a) What's it look like? What's it called? Could it be so bland as to bely trademarking? The last thing we need is another bizarre startup name like CoffUp or Blurkzee to blend in to the crowd. The best websites that keep a foothold are sparse, focusing on the tool, not the look, right? I'm thinking mostly Craigslist here.
	b) Could this be funded through a grant? Should it be? Could this be a non-profit? Should it be? Structures and methods like those create hollows for corruption to take up residence, and layers of administration that can stifle efficiency and add a burden of duty separate from a burden of civic duty. Here goes: A civic duty is something I believe almost everyone longs to bear, but has little opportunity to do so. Who doesn't want to help others? It can be a spontaneous expression of humanity. This project should embody that notion, and therefore I don't think the whole project should be bound by that structure. But it could build on contributions of that sort. If you have a charity or foundation that can help out, that's huge. Ahem, discuss.
	c) The travel piece is pretty well sewn up by now, right? Should this or could this tie into API's provided by sites like KAYAK et al?
	d) A "real" procedure, i.e., one that requires skill, depends on a Doctor or Nurse's reputation also. Is there a potential partner or methodology for this?
	e) Better minds than mine must evaluate the legal side of all of this.

It goes without saying that this should not infringe on patents, another argument for the bare-bones, web-based approach. Nor should this generate patents or intellectual copyright of any kind. This will be of enormous value to individuals, but also policymakers worldwide. Don't lock that up.

Good luck!
