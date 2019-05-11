# Joint Learning of Facial Expression and Head Pose from Speech Examples

Using the code from :

<https://github.com/davegreenwood/Joint-Learning-of-Facial-Expression-and-Head-Pose-from-Speech>

Some example predictions.

## Format

The predicted animation is in JSON format with the following keys.

* triangulation - zero based index to the xyz point data.
* translation - a list of xyz translation values, for each frame in the animation.
* rotation - a list of xyz rotation values, for each frame in the animation.
* deforms - a list of each xyz mesh point, for each frame in the animation.
