Fake News Detection
This task addresses the problem of misinformation detection in social media posts related to the Gaza–Israel context. 
It comprises two subtasks designed to evaluate textual and multimodal detection capabilities.

SubFile 1 – Binary_Multilingual_FakeNews_Detection:

==> The first subtask focuses on detecting misinformation in Arabic and English posts using textual information only. 

==> The dataset includes posts collected from Facebook and Twitter, containing fields such as author information, post URL, textual content. 

==> Each post is labeled as real or fake based on the Text Target field. 

==> The goal is to build multilingual classification models that can accurately identify misinformation across different languages and contexts.

SubFile 2 – Arabic_Cross_Modal_Inconsistency_Detection:

==> The second subtask targets Arabic posts containing both text and images. 

==> It aims to identify inconsistencies between the textual and visual content. 

==> Based on the Text Target and Img Target annotations, new labels—consistent, inconsistent, and manipulated—are generated. 

==> This enables the detection of cases where textual and visual information either align or contradict each other, supporting the development of models capable of identifying complex multimodal misinformation.

SubFile 3 - Image_Captioning_For_Conflict_Awareness:

==> Participants must build an image captioning model that generates accurate, descriptive, and unbiased captions for images related to the Gaza–Israel conflict. 

==> The images, collected from Facebook and Twitter between October 2023 and August 2025, cover events such as protests, destruction, aid efforts, and media scenes. 

==> The system should produce empathetic captions that factually describe each image’s content.

SubFile 4 - Gaza_Israel_War:

==> Contains all columns that collected from Facebook and Twitter between October 2023 and August 2025, cover events such as protests, destruction, aid efforts, and media scenes. 
