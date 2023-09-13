## Blog Post Title From First Header

Due to a plugin called `jekyll-titles-from-headings` which is supported by GitHub Pages by default. The above header (in the markdown file) will be automatically used as the pages title.

If the file does not start with a header, then the post title will be derived from the filename.

This is a sample blog post. You can talk about all sorts of fun things here.

---

### This is a header

#### Some Python Code

```python
test_loss, test_acc = model.evaluate(test_data, test_labels)
print("Test Accuracy:", test_acc)

# Save the trained model
model.save('image_classification_model.h5')
```

#### Some Java Code

```java
Node(float initialValue, NodeConnection connection, NodeLayer parentLayer){
        this.nodeValue = initialValue;
        this.nodeConnection = connection;
        this.parentLayer = parentLayer;
        if(nodeConnection.getNextNode() != null){
            // X, Y, Z = getNextNode() - 1
            posX = nodeConnection.getNextNode().posX - 1;
            posY = nodeConnection.getNextNode().posY - 1;
            posZ = nodeConnection.getNextNode().posZ - 1;
            posT = nodeConnection.getNextNode().posT - 1;
        } else if(nodeConnection.getPreviousNode() != null){
            // X, Y, Z = getNextNode() + 1
            posX = nodeConnection.getNextNode().posX + 1;
            posY = nodeConnection.getNextNode().posY + 1;
            posZ = nodeConnection.getNextNode().posZ + 1;
            posT = nodeConnection.getNextNode().posT + 1;
        } else {
            // Could not find a spot for this node, put in somewhere random.
            Random random = new Random();
            int xPos = random.nextInt(parentLayer.getDimensionLength(Dimension.X));
            int yPos = random.nextInt(parentLayer.getDimensionLength(Dimension.Y));
            int zPos = random.nextInt(parentLayer.getDimensionLength(Dimension.Z));
            posX = xPos;
            posY = yPos;
            posZ = zPos;

        }
    }
```
