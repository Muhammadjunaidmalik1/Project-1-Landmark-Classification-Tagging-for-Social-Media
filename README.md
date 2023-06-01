# Project-1-Landmark-Classification-Tagging-for-Social-Media
A Project of Udacity Deep Learning Nanodegree program  where  I learned how to build a pipeline to process real-world, user-supplied images and deployed the trained model into an app. Given an image, The app will predict the most likely locations where the image was taken. Predicted 50 Landmarks in total with 76% accuracy.


Photo sharing and photo storage services like to have location data for each photo that is uploaded. With the location data, these services can build advanced features, such as automatic suggestion of relevant tags or automatic photo organization, which help provide a compelling user experience. Although a photo's location can often be obtained by looking at the photo's metadata, many photos uploaded to these services will not have location metadata available. This can happen when, for example, the camera capturing the picture does not have GPS or if a photo's metadata is scrubbed due to privacy concerns.

If no location metadata for an image is available, one way to infer the location is to detect and classify a discernable landmark in the image. Given the large number of landmarks across the world and the immense volume of images that are uploaded to photo sharing services, using human judgement to classify these landmarks would not be feasible.

In this project, I solved this problem by building a CNN-powered app to automatically predict the location of the image based on any landmarks depicted in the image. At the end of this project, the app will accept any user-supplied image as input and suggest the top k most relevant landmarks from 50 possible landmarks from across the world.
