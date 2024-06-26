
# CRYPTIC CANVAS - The Ultimate Image/Video Colorizer

![My Image](https://drive.google.com/uc?id=1CosZ0TIWUL-nWG9jP-1ZnVkx5IQVUe2v)

[Website](https://main--cryptic-canvas.netlify.app/) 

[Demo Video](https://drive.google.com/file/d/18SRwKCNDd6M_pewOTV-dXU-WS4er2ouT/view?usp=sharing) 

Welcome to our Image Colorizer project! Our tool allows you to effortlessly add vibrant color to your images and videos. Whether you want to bring old black-and-white photos to life or simply enhance the colors in your existing media, Cryptic Canvas has you covered.

## Introduction

This README provides an overview of the features, usage instructions, and contact information for our project. Read on to learn how you can easily colorize your images and videos with our intuitive platform.

## Features

Cryptic Canvas offers several convenient options for colorizing your content:

1. **Upload Images:** Simply upload your black-and-white or grayscale images to our platform and watch them come to life with color.

2. **Link Images:** Provide a direct link to your images hosted online, and our colorizer will do the rest, adding beautiful hues and tones to your pictures.

3. **Live Image Colorization:** Experience the magic in real time by using our live image colorization feature. Just point your device's camera at the desired scene, and watch as it transforms before your eyes.

4. **Upload Videos:** Want to add color to a video clip? No problem! Upload your videos to our platform, and we'll apply our colorization algorithms to bring them to life.

5. **Link Videos:** Similar to linking images, you can also provide links to videos hosted online, and our colorizer will work its magic on them.

6. **Live Video Colorization:** Take your colorization experience to the next level with our live video colorization feature. This is mostly built for security cameras to show the video in color even at night.

## Application

Our primary objective is to enhance the quality of CCTV camera footage by converting monochromatic imagery into full-color representations.
This innovation is particularly relevant as existing color-enabled CCTV cameras typically require integrated light sources, leading to increased electricity consumption and compromising the covert nature of surveillance by revealing the camera's location.

## Getting Started

To start using Cryptic Canvas, simply follow these steps:

1. Visit our [Website](https://main--cryptic-canvas.netlify.app/).
2. Click on Live Demo button.
3. Choose the colorization option that best suits your needs: upload images, link images, live image colorization, upload videos, link videos, or live video colorization.
4. Follow the prompts to upload or link your media, or activate your device's camera for live colorization.
5. Sit back and watch as our advanced algorithms add stunning color to your content.
6. Show your newly colorized images and videos with friends, family, or colleagues.

## How to Do It Yourself

### Requirements
- Python 3.7
- Streamlit
- OpenCV
- Windows/Linux

   You can install OpenCV and Streamlit using pip:
   ```bash
   pip install opencv streamlit
   ```
   **Do not Skip any steps**

1. **Clone the Repo:**
   To get started with Cryptic Canvas, you can clone the repository to your local machine using the following command:
   ```bash
   git clone https://github.com/Aaron-Thomas-Blessen/CrypticCanvas.git
   ```
2. **Streamlit Account:**
   If you want to publish the web version of the application, you'll need a Streamlit account. Sign up at [streamlit.io](https://streamlit.io/) to get started.

3. **Getting Started:**
   Navigate to the website folder and run index.html.
   Then click on Live Demo

5. **Run Locally:**
   To run the Cryptic Canvas application locally, navigate to the project directory
   and execute the following commands in separate Terminals:
   ```bash
   streamlit run image_upload.py
   ```
   ```bash
   streamlit run image_link.py
   ```
   ```bash
   streamlit run image-live.py
   ```
   ```bash
   streamlit run video_upload.py
   ```
   ```bash
   streamlit run video_link.py
   ```
   ```bash
   streamlit run video_live.py
   ```
   Copy the local network ID and paste it into new.html link addresses respectively.
   - This increases the speed of colorization.
     
If you have the desire to publish this as a web app, then you need to upload all these files to your Git Hub and host it using streamlit for free.

## Adding large files to GitHub
To add large files to the GitHub for free you need GIT LFS.

The file "colorization_release_v2.caffemodel" has a 122 MB file size so you cannot directly push it to Git Hub.

```bash
git lfs install
```
```bash
git lfs track "*.caffemodel"
```
```bash
git add .
```
```bash
git push -u origin main
```

## Feedback

We're constantly striving to improve Cryptic Canvas to provide the best possible experience for our users. If you have any feedback, suggestions, or encounter any issues while using our platform, please don't hesitate to contact us. Your input is invaluable in helping us enhance our product and deliver exceptional results.

## Contact Us

If you have any questions, concerns, or inquiries regarding Cryptic Canvas, please contact us at [aaronthomas232200@gmail.com](mailto:aaronthomas232200@gmail.com.com) or connect with me at [LinkedIn](https://www.linkedin.com/in/aaron-thomas-blessen-390200214/) or at [Twitter](https://twitter.com/aaron_blessen). We're here to assist you and ensure that your colorization experience is smooth and enjoyable.

Thank you for choosing Cryptic Canvas. We hope you enjoy adding vibrant color to your images and videos!
