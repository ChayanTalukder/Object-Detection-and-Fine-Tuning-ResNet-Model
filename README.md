# Module One: The task is to develop a computer vision system that, given a reference image for each book, is able to identify such book from one picture of a shelf.
Computer vision-based object detection techniques can be applied in library or bookstore settings to build a system that identifies books on shelves (dataset is provided separately)
Such a system could assist in:
Helping visually impaired users locate books by title/author;
Automating inventory management (e.g., detecting misplaced or out-of-stock books);
Enabling faster book retrieval by recognizing spine text or cover designs.

# Module Two: The goal is to implement a neural network that classifies images of 37 breeds of cats and dogs, followed by fine-tuning a pretrained ResNet model.
The assignment is divided into two parts: implementing from scratch our own neural network for image classification from the Oxford-IIIT Pet dataset; then, fine-tune a pretrained network provided by PyTorch.

CNN from Scratch (PyTorch):
Designed and implemented a deep convolutional neural network inspired by ResNet-v2.
Conducted an ablation study by testing different architectural choices (e.g., skip connections, depth, number of filters) to analyze their impact on performance.
Transfer Learning with ResNet (PyTorch)

Fine-tuned a pretrained ResNet (ImageNet weights):
Pretrained layers already extracted strong general features (edges, textures, shapes).
Adapted the top layers to classify pet breeds.
Achieved ~90% accuracy, showing how pretrained weights were already highly effective and that fine-tuning outperformed training from scratch.



