# Ex.08 Design of Interactive Image Gallery
# Date:
# AIM:
To design a web application for an inteactive image gallery with minimum five images.

# DESIGN STEPS:
## Step 1:
Clone the github repository and create Django admin interface.

## Step 2:
Change settings.py file to allow request from all hosts.

## Step 3:
Use CSS for positioning and styling.

## Step 4:
Write JavaScript program for implementing interactivity.

## Step 5:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
'''
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Image Gallery</title>
</head>
<body>
    <header style="text-align: center; background-color: #333; color: white; padding: 1rem 0;">
        <h1>Beauty of Nature</h1>
    </header>

    <div style="white-space: nowrap; overflow-x: auto; padding: 1rem;">
        <div style="display: inline-block; margin-right: 10px;" onclick="openModal(this)">
            <img src="img1.jpg" style="height: 200px;">
        </div>
        <div style="display: inline-block; margin-right: 10px;" onclick="openModal(this)">
            <img src="img2.jpg" style="height: 200px;">
        </div>
        <div style="display: inline-block; margin-right: 10px;" onclick="openModal(this)">
            <img src="img3.jpg" style="height: 200px;">
        </div>
        <div style="display: inline-block;" onclick="openModal(this)">
            <img src="img4.jpg" style="height: 200px;">
        </div>
        <div style="display: inline-block; margin-right: 10px;" onclick="openModal(this)">
            <img src="img5.jpg" style="height: 200px;">
        </div>
        <div style="display: inline-block; margin-right: 10px;" onclick="openModal(this)">
            <img src="img6.jpg" style="height: 200px;">
        </div>
    </div>

    <div id="modal" style="display: none; position: fixed; z-index: 1; left: 0; top: 0; width: 100%; height: 100%; background-color: rgba(0,0,0,0.9);">
        <span style="position: absolute; top: 15px; right: 35px; color: white; font-size: 40px; font-weight: bold; cursor: pointer;" onclick="closeModal()">&times;</span>
        <img id="modalImage" style="display: block; margin: 5% auto; max-width: 80%;">
    </div>

    <script>
        function openModal(element) {
            var modal = document.getElementById("modal");
            var modalImg = document.getElementById("modalImage");
            modal.style.display = "block";
            modalImg.src = element.querySelector("img").src;
        }

        function closeModal() {
            document.getElementById("modal").style.display = "none";
        }
    </script>
</body>
</html>
'''
# OUTPUT:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/48e74122-3e5e-4481-9e45-638775bca06b" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1b626a47-b2b9-48a9-918a-9dc9e406666f" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a7ea7272-2c73-4587-adb2-6a74c75acd10" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f6961b09-0cbd-4c52-b78c-be595170412c" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/684d5ba2-3685-4a4f-9922-41a594b0c7a1" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/406df77e-46c2-4f77-b09a-193f6ca0e745" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1f7b8ecc-c630-4553-8dcc-07b5f37d4354" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f9f5463a-eda7-4606-91ad-2e28405d56ea" />









# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
