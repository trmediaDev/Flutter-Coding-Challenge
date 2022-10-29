# Freeconvert Flutter Coding Challenge

## Project Backstory
Getty Images is a company that collect stock images. They currently have a great website that showcase their stock photo catalogue. They want to expand their business by building a Mobile App to reach more users.

You just got the contract to create the Mobile App to showcase these catalogues.

## Project Statement
For the initial release of this Mobile App, the business team wants to include two pages. One page displays the catalogue items and another page shows a shopping cart.

The company stores all of its images in a single JSON file. This image collection is located at https://picsum.photos/v2/list?page=1&limit=100 in the following format

```json
[
   {
      "id":"0",
      "author":"Alejandro Escamilla",
      "width":5616,
      "height":3744,
      "url":"https://unsplash.com/photos/yC-Yzbqy7PY",
      "download_url":"https://picsum.photos/id/0/5616/3744"
   },
   {
      "id":"1",
      "author":"Alejandro Escamilla",
      "width":5616,
      "height":3744,
      "url":"https://unsplash.com/photos/LNRyGwIJr5c",
      "download_url":"https://picsum.photos/id/1/5616/3744"
   }
   ...
]
```

The list of images is sorted in descending order such that the latest images are at the top of the list. The number of images retrieved from the API can be changed by changing the `page` and `limit` query parameters when calling the API.

The company's business team wants a Catalogue page with each image in a square tile that takes up half of the screen. 

| Catalogue |   |
|---|---|
|  Image 1 | Image 2  |
|  Image 3 | Image 4  |
|  Image 5 | Image 6  |

Users can tap to select or unselect images on the list which get added to or removed from a shopping cart. 

Users can access the Shopping Cart page by tapping on a shopping cart icon located on the top right corner of the Catalogue page. This icon should have a badge to indicate the number of items selected. When the user taps on the shopping cart icon, it takes them to the Shopping Cart page with only the items selected from the Catalogue page displayed in a list with more details such as the author's name and image size. Users should be able to remove items from the shopping cart page. If removed, those items should be unselected from the Catalogue page as well.

They also provided some insight into the company's user base. Most of their users use mid-range mobile devices with 4G+ connection speed.

Your task is to build a Mobile Application for the user group mentioned above using the Flutter framework that meets the above requirements. 

## Before you start coding
The time limit for completing this project is 4 hours. We don't expect you to submit a 100% completed solution. We value maintainable code, following software development best practices, and your ability make decisions based on data presented to you.

## Your submission

Create a file called `solution.md` and add a short paragraph or two explaining your solution and any assumptions you have made to scope the given problem. 

Once everything is completed, remove the `build` folder and `zip` the entire project and send it to `admin@trmedia.ca`
