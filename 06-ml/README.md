# Machine Learning for Creative Expression

- 📊 [ML Slides](https://docs.google.com/presentation/d/18g8XpmfR1thyAQmVfUEBwloaoOd0rfVCbCk5i3gmX6A/edit?usp=sharing)

## What is Machine Learning?

- Understanding AI, Machine Learning, and Deep Learning
- Applications of ML in art, design, and creative practice
- What is a "[pre-trained model](https://docs.ml5js.org/#/learn/ml5-glossary?id=pretrained-model)"?
- Introduction to [ml5.js](https://ml5js.org)
- Image classification and training your own models
- Body, hand, and face tracking for gesture-based interaction
- How models are trained and the politics of training data

## Image Classification

### References

- 🎥 [A Beginner's Guide to Machine Learning with ml5.js](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/0-introduction/1-introduction)
- 🎥 [ml5.js: Image Classification](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/1-classification/image-classification)
- 🛠️ [Teachable Machine](https://teachablemachine.withgoogle.com/)
- 🎥 [Teachable Machine video tutorials](https://thecodingtrain.com/tracks/teachable-machine)
- 💻 [Image Classification with MobileNet](https://editor.p5js.org/ima-cc/sketches/hnypvefPa)
- 💻 [Teachable Machine](https://editor.p5js.org/ima-cc/sketches/BF13z6VK8)

## Body, Hand, and Face Tracking

### BodyPose (tracking body movement)

- 🎥 [2D Pose Estimation - MoveNet](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/7-bodypose/pose-detection)
- 🎥 [3D Pose Estimation - BlazePose](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/7-bodypose/blazePose)
- 📖 [ml5.bodyPose Reference](https://docs.ml5js.org/#/reference/bodypose)
- 💻 [Nose Tracking](https://editor.p5js.org/ima-cc/sketches/-O1ytBljN)
- 💻 [Multiple Body Parts](https://editor.p5js.org/ima-cc/sketches/DO1G9JSR6)
- 💻 [Hat Overlay](https://editor.p5js.org/ima-cc/sketches/Pey7IuSq1)

### HandPose (tracking hand gestures)

- 🎥 [Hand Pose Detection](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/hand-pose)
- 🎥 [Interactive Fridge Magnets](https://youtu.be/72pAzuD8tqE) by Patt Vira
- 📖 [ml5.handPose Reference](https://docs.ml5js.org/#/reference/handpose)
- 💻 [All Hand Keypoints](https://editor.p5js.org/ima-cc/sketches/yOy6F5Pze)
- 💻 [Hand Painting](https://editor.p5js.org/ima-cc/sketches/NdZHLq3BO)
- 💻 [Painting - Stroke Weight](https://editor.p5js.org/ima-cc/sketches/qDcQcLq1m)
- 💻 [Particles](https://editor.p5js.org/ima-cc/sketches/sfbBqQc-6)

### FaceMesh (tracking facial features)

- 🎥 [Face Mesh with ml5.js](https://thecodingtrain.com/tracks/ml5js-beginners-guide/ml5/facemesh)
- 🎥 [Interactive Dandelion](https://youtu.be/FlBRSIz5AcQ) by Patt Vira
- 📖 [ml5.faceMesh Reference](https://docs.ml5js.org/#/reference/facemesh)
- 💻 [All Face Keypoint](https://editor.p5js.org/ima-cc/sketches/v9tiP9WS1)
- 💻 [Tracking Specific Parts](https://editor.p5js.org/ima-cc/sketches/NLbTCBgWi)
- 💻 [Custom List (Lips)](https://editor.p5js.org/ima-cc/sketches/ash9qKQz0)
- 💻 [Blow Bubbles](https://editor.p5js.org/ima-cc/sketches/mp6cgZwIE)

## Additional Inspiration

- [Emoji Scavenger Hunt](https://emojiscavengerhunt.withgoogle.com/) - Google Creative Lab
- [Teachable Snake](https://experiments.withgoogle.com/teachable-snake) - Vince MingPu Shao
- [Posenet Sketchbook](https://googlecreativelab.github.io/posenet-sketchbook/) - Maya Man
- [Messa di Voce](https://vimeo.com/2892576) - Golan Levin & Zach Lieberman
- [Melody Painter with HandPose](https://www.instagram.com/p/C4WozrtsZ4r/)

## Supplemental Reading

- 📖 [A People's Guide to AI, 2nd Edition](https://store.alliedmedia.org/collections/a-peoples-guide-to-tech/products/digital-download-a-peoples-guide-to-ai-2nd-edition) - Allied Media
- 📖 [Chapter 10: Neural Network, Nature of Code](https://natureofcode.com/book/chapter-10-neural-networks/) - Daniel Shiffman
- 🎥 [How we teach computers to understand pictures](https://www.youtube.com/watch?v=40riCqvRoMs) - Fei-Fei Li
- 🎥 [Machine Learning for Human Creative Practice](https://vimeo.com/287094397) - Rebecca Fiebrink (Eyeo 2018)
- 📖 [Humans of AI](https://humans-of.ai/editorial) - Philipp Schmitt

## Assignment

### Reading

- 📖 [Excavating AI: The Politics of Images in Machine Learning Training Sets](https://www.excavating.ai) by Kate Crawford and Trevor Paglen
- 📖 [Mixing movement and machine](https://medium.com/artists-and-machine-intelligence/mixing-movement-and-machine-848095ea5596) by Maya Man

### ML Sketch

For this assignment, experiment with interactivity and machine learning models. You can try one or both of the following approaches.

- Train your own image classifier using [Teachable Machine](https://teachablemachine.withgoogle.com) and create a p5.js sketch where the detected classifications affect elements on the canvas.
- Pick a "landmark tracking" model (BodyPose, HandPose, or FaceMesh) and use the detected points to control elements of your sketch. Play with the relationship between physical gesture and other computational techniques.

Along with screenshots and notes on your creative process (what you tried, challenges, what you learned), reflect on how the readings connect to your experiments. Here are some prompts to consider:

- Crawford and Paglen show how ImageNet's categories reveal "politics, ideology, prejudices" rather than objective truth. What assumptions, values, or worldview are embedded in the labels you created? What did your sketch decide was important to track or respond to, and what did it ignore?
- Maya Man writes that working with Bill T. Jones taught her "to focus less on what the machine learning model could do and more on what it could help convey." Does the technology serve your concept, or do you find yourself building around what the technology could do?
- Both readings explore how AI systems interpret and classify human bodies and actions. Excavating AI argues that "images do not describe themselves", but rather the meaning comes from who labels them and how. In your sketch, how does the ML model "see" or interpret? What gets recognized, misrecognized, or missed entirely? How might different people experience your sketch differently?
