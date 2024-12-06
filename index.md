# Documents are understandable with proper headers
Let us now add an image of a space-ship.

![An image of a spaceship](https://stablediffusionweb.com/image/3256652-spaceship-bridge-view-from-earth-orbit)

## Github allows us to add code blocks.
This will be helpful for creating and sharing notes with each other and explaining each others code snippets. We can also specify the syntax to be followed. For example, the following code block is for Python and is specified as such.
``` python
import seaborn as sns
import matplotlib.pyplot as plt

sns.set_style("whitegrid")
data = sns.load_dataset("titanic")
sns.displot(data=data, x="age", hue="pclass", kde=True)
plt.show()
```
