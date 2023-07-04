---
title: "Data annotation platform hell"
description: "A list of non mobile friendly data annotation platforms. Of which there exists none."
pubDate: "2023-07-04"
---
DAP = Data annotation platform

A good machine learning project also requires a quality dataset. If the dataset doesn't exist yet and you don't want to spend exorbitant amounts of money to create one, there's only one option left: create it yourself.

I've been stuck in this dilemma for a while. I want to pursue some potentially exciting projects, but I lack existing data for them.

Therefore, I've decided to explore the idea of creating a dataset myself, but without relying on a computer. But rather a phone.

I need a mobile solution so I can work on the go, during my commute or while waiting in line. As this is just a little side project.

Initially, I thought this requirement wouldn't be so niche, but it turns out it is.

I've researched various DAPs, but none of them seem to meet my requirements. All the DAPs are not usable on mobile, most have a free plan, but it's limited in some way. I think I have checked out all the big players in the market, but I might have missed some.

Below, I've listed the options I've considered along with my thoughts on how they fulfill the requirements.

If you happen to know any other DAP that meet the requirements, please share them with me.

For now I might consider contributing to cvat to make it somewhat useable on mobile or create a very simple webapp myself.

# Requirements
- Free
	- Dataset can be public in exchange for platform being free
	- Sync between devices, so I can work on the go
  - Some costs are fine, but not too much
- Bounding Boxes
	- Very basic feature all of them have
- **Usable on Mobile**
- Open Source is always nice

# Candidates
## cvat
https://www.cvat.ai/
- Freemium model
	- Limitations to the dataset size etc, but couldnt find the limits
- Barely useable on mobile
	- Annotations can be created, but not resized
	- UI does not scale down, but website can be scrolled to be used
- Open source
	- Go fix it yourself?

# Unusables
## Host it yourself/ Local
### Scalabel
https://scalabel.ai/
- Open source
- Not tried
 
### Label studio
https://labelstud.io/
- Not useable on mobile
	- Large parts of screen blocked by UI Elements
	- Annotations cannot be created
- Open source

## Roboflow
https://roboflow.com/
- Free
	- dataset is public
- Not useable on mobile
	- Entire screen blocked by UI Elements
- proprietary

## Dataloop
https://dataloop.ai/
- Free?
- Not useable on mobile
	- Large parts of screen blocked by UI Elements
	- Annotations can be created, but not edited
	- Image cannot be panned
- proprietary

## Ango.ai
https://ango.ai/
- not free anymore
- Not useable on mobile
	- Some parts of screen blocked by UI Elements
	- Annotations cannot be created
- proprietary

## Labelbox
https://labelbox.com/
- limited Free
- Not useable on mobile
	- Screen blocked by UI Elements
	- Image cannot be panned
	- Annotations cannot be created
- proprietary

## v7labs
https://www.v7labs.com/
- free?
	- Free Edu Account
	- Days Left 730 Annotation Credits 100 Managed file storage left 50,000
- work email wtf
	- common email domains blocked for registration
- Not useable on mobile
	- Screen blocked by UI Elements
	- Image cannot be panned
- proprietary

## Supervisely
https://supervisely.com/
- Free?
- Barely useable on mobile
	- Some parts of screen blocked by UI Elements
	- Annotations can be created, not edited
- proprietary?

## MakeSense
https://www.makesense.ai
- Local data
- Not available for small screens
- Open source

## Others
- ScaleAi
	- No free plan
- SuperAnnotate
	- Limited free Academic access??
