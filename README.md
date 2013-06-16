Social Whales
============

**BACKGROUND**

Several whale species are currently endangered. Biologists struggle to help them survive, but collecting information about whale migration paths and distribution of their population is not easy. Whales live under water, they travel huge distances, and it's hard to spot and identify them. 

One of the principle methods for whale tracking is based on photo identification.
Biologists go on expeditions, take a lot of pictures of whatever whales they see, come back home and manually compare these pictures with the pictures they have already collected in a catalog. Whales usually have some characteristic patterns on their backs or fins that uniquely identify them like fingerprints do for humans. Biologists use these patterns in order to match new pictures with pictures of known whales. Each new match adds information about a particular whale. 

As you can imagine, this way of collecting information is pretty slow and resource-consuming!

At the same time, there is a wide range of companies organizing whale watching trips and thousands of engaged whale watches going on boats to see whales and take thousands of pictures. Can't those pictures be used to help the biologists to collect information?

---

**PROJECT IDEA**

The Social Whales project is about building a web service for:

- uploading and annotating photographs of whales
- browsing the accumulated whale catalog
- aquiring statistics about whale migration paths and distribution

The project idea and related literature is described in [this presentation]().

---

**THIS REPOSITORY**

This repository is used for the web service development. Currently, we are implementing [this use case](https://docs.google.com/document/d/1t2_9UyNxyItiv57h1jb1HqGaY2zmxZ8Tukwc3OoXFTk/edit?usp=sharing).

---

**PHOTO IDENTIFICATION ALGORITHM**

Our main photo idenfication algorithm implemented in Matlab is stored in [this repository](https://github.com/eovchinn/WhalePhotoID_MATLAB).

This algorithm currently works with pictures of [blue whales](en.wikipedia.org/wiki/Blue_whale‎), largest animals that have ever lived on Earth, are on this list. We plan to extend it for other whale species, if the project is succesful. 

