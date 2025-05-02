# What is LurkHub?

Hi I'm Leslie and I made LurkHub to store my internet bookmarks and other stuff. I like using Git and GitHub so storing them in a repo there felt like a natural fit for me. As I was making it I decided to add a section to store articles I wanted to read later and a section to add RSS feeds. I'm also testing the ability to make public posts. I made this app to scratch an itch I had but you are welcome to use it as well if you wish. Any data you store on LurkHub is stored on your GitHub account.

# Bookmarks
Bookmarks 

![image](https://github.com/user-attachments/assets/d37259d6-2736-496f-8a8c-8c360f2b875e)

A bookmark can have tags added which allows them to be filtered with the tag cloud:
![image](https://github.com/user-attachments/assets/14f1db53-8cba-4b3b-8aec-4b71305bc4ba)

The bookmark data is stored as a JSON file in the `lurkhub-data` private repo:
![image](https://github.com/user-attachments/assets/3df89fbf-2c44-42fd-9927-0c080f5238d3)

**Data Format**
```json
{
  "fields": [
    "id",
    "title",
    "url",
    "tags",
    "created"
  ],
  "values": [
    [
      "6903bf7a-8de9-4505-8ad7-91fce630837d",
      "Folklore.org: The Original Macintosh",
      "https://www.folklore.org/0-index.html",
      "tech,history",
      "2025-05-02T11:42:54.286Z"
    ],
    [
      "e65d8bb7-803d-460c-bb8a-db6cd09212bd",
      "Radio Garden",
      "https://radio.garden/",
      "radio",
      "2025-05-02T11:43:13.529Z"
    ],
    [
      "13d16e06-af27-43dc-bbb5-c9873d120854",
      "Ghostty",
      "https://ghostty.org/",
      "software",
      "2025-05-02T11:43:26.770Z"
    ],
    [
      "22c858a7-1d17-432a-b322-c4a6eeb26c27",
      "SomaFM",
      "https://somafm.com/",
      "radio",
      "2025-05-02T11:43:42.757Z"
    ],
    [
      "e5a5c279-2e07-491b-aa1d-b64841f94b92",
      "Obsidian - Sharpen your thinking",
      "https://obsidian.md/",
      "software",
      "2025-05-02T11:44:06.149Z"
    ],
    [
      "9fca1c4f-17e4-493f-89c1-6c83c692009b",
      "Standard Ebooks",
      "https://standardebooks.org/",
      "books",
      "2025-05-02T11:44:19.481Z"
    ],
    [
      "675e0345-a75f-47a8-b56d-006175768883",
      "Saturday Morning Breakfast Cereal - Cheetos",
      "https://www.smbc-comics.com/",
      "comics",
      "2025-05-02T11:44:54.645Z"
    ],
    [
      "4f3e3276-4902-4b8f-86d6-23bbecb552ad",
      "Julia Evans",
      "https://jvns.ca/",
      "tech,dev",
      "2025-05-02T11:53:58.509Z"
    ]
  ]
}
```

# Articles

Articles lets me store links I want to read later:

![image](https://github.com/user-attachments/assets/5b3cdbd8-6e3e-4bdd-b5b7-12359363db13)



# Feeds

I've recently created a section for RSS Feeds. It's not a full RSS reader but instead shows a list of subcribed feeds with the most recently updated at the top. It shows the most recent item in the feed which can be clicked to go directly to that item:

![image](https://github.com/user-attachments/assets/c254c684-3302-4956-8d01-4afb56af79cb)

Clicking the feed name will display all the feed items:
![image](https://github.com/user-attachments/assets/9e347519-34a3-4c66-92ca-3edd8865f9ba)


# Posts

LurkHub can let you make posts in markdown format. They are stored in a public `lurkhub-posts` repo on your GitHub account. Any posts you make are viewable at `lurkhub.com/@username`
