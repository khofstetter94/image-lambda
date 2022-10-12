# image-lambda

- a description of how to use your lambda.
  - Once a photo is downloaded into the 'kmh-photos-lab' bucket, the lamdba function will be triggered (specifically for .png photos), then the 'images.json' file that already exists in the bucket will be updated with the new photo. The photo will appear as an object in an array with the properties for the photo's name, size, and file type.
- a description of any issues you encountered during deployment of this lambda.
  - One obastacle was finding the 'type' of the image since it didn't already come with the event like the other properties, but it could be made from the 'name' property since the name ends with the file extension.
- a link to your images.json file.
  - [images.json](https://kmh-photos-lab.s3.us-west-2.amazonaws.com/images.json)
