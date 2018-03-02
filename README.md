# What is this?

This is my recipe for a meal replacement shake inspired by products like Ensure and Soylent. The idea is…

 - **Dirt cheap @ $3/day**: Soylent etc. costs over 3x that. A standard diet at the same level of convenience (i.e., fast food, delivery pizza, take-out, or TV dinners) easily costs over 5x that.
 - **Vegan**: This can be scaled up massively without nuking the environment. Also, you know, it's nice not to have to eat animal flesh just to survive.
 - **Total nutrition**: ~~This article says X food causes cancer!~~ ~~Am I getting enough vitamins?~~ ~~I don't think I'm getting enough protein.~~ ~~I keep getting sleepy after lunch.~~ ~~Isn't this fattening?~~ All these food-related problems are solved for you.
 - **High protein**: 150g of protein per day. To get this much protein, you'd have to eat 24 ounces of steak or 3 lbs of cottage cheese (2 standard containers). High protein helps you feel full throughout the day.
 - **Convenience**: Cooking, washing dishes, waiting in drive thrus, walking through grocery stores like an animal searching for feed—is this really how you want to spend your life? These chores become no longer a necessity to survive. Eating out or cooking becomes a *choice*, something you decide do for pleasure. And sometimes you just have better things to do than scrub a nasty pot or fill up the garbage with fast food wrappers. But it's up to you. At least you can have the *freedom* to choose.
 - **Doesn't taste nasty**: It tastes like nothing! No, not cardboard, *nothing*! You have to try it to believe it.

# Usage

Take a look at the spreadsheet in this repo. Everything is delineated by weight, so you need a gram scale. Use 1600mL of water (give or take depending on your own personal taste).

You can find all the ingredients on Amazon. I recommend buying the smallest consumer quantities you can just to see if you like it first. If you like it, buy everything in bulk and make 1 month batches.

I recommend using a 1 gallon pitcher that seals (e.g., Sterilite). A stainless steel mixing ball helps.

To increase or decrease calories, adjust the amount of maltodextrin and/or soybean oil. These ingredients (more so maltodextrin) don't provide much useful nutrients other than its calories.

If you have a problem with the formula, feel free to submit a PR.

## Being able to diff .xlsx files with git

``$ ./enable-xlsx-diffs.sh``


# Rationale

## Why pea protein?

 - One of the cheapest protein sources. It requires less resources to extract protein from peas than soy. Bulk prices for pea protein tend to be less than bulk prices for soy protein.
 - Yes, pea protein by itself tastes bad. But the flavor problem can be solved. It's possible to (1) mask the bad (bitter, grassy, slightly nutty) flavor of pea protein, (2) combine pea protein with "good" flavors that happen to possess some of the "bad" flavor characteristics of pea protein, effectively turning it into an advantage by accentuating the other flavors, and (3) use the bitterness of pea protein to form a complete aggregate of flavors, thus more closely approximating real food, as opposed to a milkshake type of drink where its creators deliberately avoided bitter ingredients.
 - Plant-based--sustainable, environmentally friendly, doesn't require animals, can be scaled up.
 - Very clean compared to the alternatives in terms of heavy metal content (c.f., rice, whey) or inherent health risks.

### Masking the taste of pea protein

#### Adding ingredients that co-opt the off flavors of pea protein

The idea is to fool your tasting mechanisms into perceiving the bad flavors of peas as parts of other ingredients which can pull off having those flavors.

 - ~~**Hemp protein** has a grassy, nutty taste.~~
 - **Rice bran** has a slight nutty taste.
 - **Peanut flour** is very nutty and beany.
 - **Cocoa powder** is bitter.

#### Menthol to anesthetize tastebuds

This is really the [secret weapon][7]. It can't taste bad if you can't taste it at all.

The goal is to use just enough menthol to disrupt your tastebuds but below the threshold where you can actually taste the menthol. Menthol itself [is bitter][9]. We don't want a minty/menthol-flavored meal replacement.

#### Sucralose (sweetness) to block bitterness

Sucralose is preferable to regular table sugar not because of health/nutrition concerns but because sugar is not nearly as sweet as an equivalent weight of sucralose. The amount of sugar to replace even a tiny amount of sucralose would be too much to even dissolve.


## On maltodextrin and sugar

I'm looking into the risks of relying heavily on maltodextrin. I have seen mentions of people getting insulin resistance from it, but nothing from a credible source. Nevertheless, it's worth hedging our bets by substituting oat flour or plain old sucrose (which actually has a lower GI than maltodextrin) in place of some maltodextrin. It seems to make sense, at least intuitively, that chronic insulin spikes would wear out your pancreas as has been suggested.

As an aside, it's worth mentioning that Ensure, which has been around for ages with years worth of scientists on payroll optimizing its formula, [has maltodextrin (from corn) and sugar as its first ingredients][1]. It is marketed to old people, many of whom are no doubt diabetic or pre-diabetic. It's obvious that maltodextrin was chosen for economic reasons rather than health reasons. Even so, it's still nice to know that we wouldn't be pioneers (read: guinea pigs) in getting most of our calories from maltodextrin.

## On sucralose

It has been [known][2] that sucralose (or any non-nutritive sweetener including stevia) [may alter gut bacteria that digest glucose][3]. Since this is something we may be consuming daily, even small, tangential risks like this can compound over the course of multiple years.

That said, ["the results from studies conducted in healthy lean adults have reported that sucralose does not affect glycemic or hormonal responses to the ingestion of glucose or other carbohydrates"][4]. Only in obese people were the detrimental effects seen with sucralose (other non-nutritive sweeteners notwithstanding). This solution (rather than changing the ingredients): Don't be obese. Anyone who is consuming food replacements long-term is or will be lean, so this shouldn't be too much of a concern.

### Alternatives?

Why not just replace sucralose with something else? Surely there are plenty of other options. Problem is, there just aren't any good ones. I'm open to any viable alternatives to sucralose, but so far, I haven't found any.

#### Sugar

The downsides to replacing sucralose with regular sugar (sucrose) may be more serious. Tooth decay is a well-understood risk. Sugar is nowhere near as sweet as sucralose by weight, so there would have to be loads of it to replace it. I think there is enough propaganda against sugar out there already that I don't need to elaborate on why this (is?) could be a bad idea.

#### Other non-nutritive sweeteners

Replacing sucralose with other non-nutritive sweeteners would be worse as well. There's a reason sucralose is the de facto standard. Sucralose is very similar to sucrose, structurally, which offers a clue to its behavior. It's as likely to participate in irrelevant, third party reactions as sucrose is. In the body, the main difference between it and sucrose is that it passes right through and gets excreted.

##### Stevia

Sucralose has been used for decades, long enough that there are millions of people who have reached retirement age having consumed sucralose from day one. The same cannot be said for stevia, which has only been used in its extracted form since about 2008. (Yes, South American natives ate the leaves--but not its powder extractive--for thousands of years; very analogous to coca leaves vs. cocaine.) Stevia remains very much mysterious and seems to get a pass [for just being natural][5]. For example, imagine that, ["Some studies show that steviol at high dosages may have weak mutagenic activity,"][6] were said about *any* artificial sweetener. Imagine how the Whole Foods clientele or the European Union would react to it, especially if it's being touted as a safe alternative that should be consumed as much as you want. But stevia is okay no matter what--it's *natural* after all. I hope that anyone interested enough in non-natural future food that they are reading this would appreciate a distrust for that attitude and any conclusions drawn on its basis. A chemical that comes from a plant is not inherently safer than a chemical designed in a lab. All else equal, plant chemicals (aside from nutrients and vitamins) are assumed to be dangerous because plants only evolve the production thereof to poison animals that eat it. So far, I don't think there is enough evidence to comfortably contradict that null hypothesis in the case of stevia. For better or worse, plenty of people are willing to be guinea pigs. So we'll see.

##### Sugar alcohols

Sugar alcohols (e.g., xylitol) aren't sweet enough. Some give people diarrhea. Also, the sweetness:dollar ratio just isn't there.

##### Other artificial sweeteners

Other non-nutritive sweeteners, such as aspartame, acesulfame K, saccharin, etc. seem to be less ubiquitous and more expensive than sucralose. Granted, I haven't researched these as much.

## On flavoring

### Anti-flavor

The ideal food replacement drink is flavorless.

In general, specific flavors work in the short term, but everyone gets tired of them. It seems universal among all humans. I think that's why fast food/coffee places have things like Pumpkin Spice, McRib, or Shamrock Shake only for a limited time because people wouldn't buy them if they stayed on the menu forever. This is an example of the market having discovered something about our psychology: flavor fatigue. I think this is an evolutionary adaptation to encourage us to consume a varied diet that is likely to cover more essential nutrients overall.

Flavor fatigue would seem to pose an obstacle to our goal here. But is it possible to get tired of *no* flavor (the absence of flavor)? In my experience that hasn't happened. Where there is no smell and no noticeable taste, there is nothing to remember to get tired of.

Ideally, the baseline recipe should have zero net flavor, and by that I mean that every component (which may be flavorful in isolation) ought to sum to zero flavor because they all cancel each other out. The goal is an ambiguous taste that lights up too many taste receptors for it to be identified as anything more specific than *sustenance*.

Bottom line: If someone were to take a sip for the first time, their first thought shouldn't be like, "That tastes like chocolate." It should be, "That felt like food."

### Novelty flavors

If you must, these can be added to a single day's batch. I discourage preparing large quantities of powder with a flavor built-in, because you don't know how soon flavor fatigue would kick in and make it all undrinkable.

#### That work

 0. coffee; decaf instant coffee is ideal IMO
 0. cinnamon, nutmeg, ginger, clove, or combinations thereof (i.e., pumpkin spice)
 0. vanilla
 0. chocolate via Nesquik (cheapest), chocolate syrup, or cocoa powder + sweetener

#### That don't work

Yes, I have tried these, and they all suck.

 - propylene glycol-suspended food flavorings typically used for e-cigarette/vape liquid; e.g., LorAnn Oils
 - Kool-Aid packets
 - mint
 - blending in berries, fruits, or any solid foods for that matter
 - curry
 - anything savory

## On bad ingredients

I spent several months tweaking the formula before arriving at what I have now. That isn't to say this is finalized—it is a living, evolving document. In the process, I tried many bad ingredients so you don't have to.

### Whey protein

 0. The obvious, somewhat ideological issue of it being non-vegan.
 1. If you let it go bad, it will smell like a rotting corpse.
 2. Whey lacks any bitterness, saltiness, or astringency. This would seem like a good thing…if perhaps you were making a dessert product instead of something that's supposed to replace a traditional meal that has a full spectrum of flavors builtin.
 3. Virtually all cheap whey protein have non-trivial levels of heavy metals—more so with Chinese whey, which dominates the market. (Pea protein, on the other hand, cannot have any non-trivial amounts of heavy metals because the pea plant does not uptake heavy metals from soil.)
 4. Hormones (e.g., estrogen, progesterone) from cow milk.
 5. Expensive. It costs double what soy or pea protein costs.

### MSG or savory agents

I had the idea of using MSG to impart the "umami" (read: savory) flavor profile. There is one known alternative to MSG that provides some savory flavor—Ajitide® I+G (Disodium 5’ Inosinate + Disodium 5’ Guanylate), which I also tried.

 0. MSG can cross the blood-brain-barrier and cause [brain damage at doses normally found in food][8]. Yeah, yeah, I was also a skeptic before who would say, "This is pseudoscience. Glutamate is just an amino acid. It's not any different than eating any protein source." Just refer to that study. Digestion is more complicated than that simplistic model. There are many cases of amino acids being used in isolation to cause specific effects.
 1. Ajitide I+G doesn't have the same deleterious effect as MSG. Problem: Disodium 5'-guanylate is made from fish. It would seem silly to make the recipe non-vegan for the sake of this one ingredient that offers dubious improvements to the overall taste.

There are some other savory agents often cited like yeast extract, nutritional yeast, tomato extract, and kombu seaweed, but the only reason they are savory is that they happen to be naturally high in glutamate (i.e., MSG). By the way, using these ingredients is a way food manufacturers get away with saying they removed MSG from their products.

Making the recipe high in protein (pea protein) is enough to make the recipe slightly savory. After all, the evolutionary purpose of the "umami" taste is to encourage us to consume protein, so there you go.

### Psyllium husk powder

This absolutely destroys the texture of the final product. Being mostly soluble fiber, it absorbs water until the entire thing has the texture of pudding. Very unappetizing. I think this applies to all soluble fibers.

### Masa de harina corn flour

The one benefit of this is that it's dirt cheap (at least in the USA). It has a terrible, gritty texture that scratches your throat as you drink it.

## TODO

### Using another fiber source

Hemp protein works for this. It provides protein, adds to the flavor profile, and is of the preferable insoluble type of fiber. Problems:

 0. It's expensive.
 1. There are always black hemp husks that never quite dissolve and sink to the bottom.
 2. Texture is a bit gritty.

**Rice bran**, corn bran, or wheat bran are cheap and [high in insoluble fiber][10].

![nutrition data for stabilized rice bran from manufacturer](https://i.imgur.com/jv5MIhs.png)

### Write more detailed explanation on preparation techniques

  [1]: https://ensure.com/nutrition-products/ensure-original
  [2]: https://www.npr.org/sections/thesalt/2014/09/17/349270927/diet-soda-may-alter-our-gut-microbes-and-the-risk-of-diabetes
  [3]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4615743/
  [4]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4661066/
  [5]: https://en.wikipedia.org/wiki/Naturalistic_fallacy
  [6]: https://www.mskcc.org/cancer-care/integrative-medicine/herbs/stevia
  [7]: https://www.ncbi.nlm.nih.gov/pubmed/10981623
  [8]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2802046/
  [9]: https://www.ncbi.nlm.nih.gov/pubmed/12502523
  [10]: https://www.prebiotin.com/prebiotin-academy/fiber-content-of-foods/
