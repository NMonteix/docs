# Create a new template.

There are several steps to creating a new template. Before you begin, you may want to review our [documentation on metadata](../before-you-begin/metadata.md).

When you're ready to make your template, navigate to Tropy &gt; Preferences and click to the Templates section. When you first open the Preferences pane, New Template will be the default, but if you click over to one of the other templates, you can get back to New Template by clicking on it in the Template drop-down box or by clicking the first button next to the drop-down.

## Metadata about your template![](../.gitbook/assets/template-header-2x.png)

Your template starts with metadata about the template.

Each template requires a name and a URI at minimum. The creator and description are optional but valuable if you ever intend to share the template you create.

* **Name**: You can name your template anything. We recommend that you name it with as much specificity as possible. For instance, it's likely that you're creating a template to deal with materials from one particular institution, so it makes sense to name your template with the name of the institution. If you're working with one particular collection with unique metadata, name your template after the collection. For example, "National Archives" might be sufficient, or you might want to call your template "National Archives RG 45" if your template would have to be revised in order to fit other record groups at the National Archives.
* **URI**: The URI has to be a unique term within your Tropy installation. Tropy auto-generates a URI for you, but you can change the URI to something more memorable. We recommend that you think of the URI in broad terms: if you ever intend to share it, you should give it a URI that will be unique no matter where it goes. Templates that come with Tropy, for instance, have URIs that look like this: `https://tropy.org/v1/templates/[name of template]`. If you have a domain that belongs to you, it might make sense for you to give your Tropy templates URIs connected to your web domain. But you could also give your template a URI as basic as "national-archives" or "us-NatArch."
* **Type**: This field is where you select either Item, Photo, or Selection level template. Whichever you select here will determine which level your template is visible at in the metadata pane.
* **Creator**: For individuals, the creator should be your name. If you are creating a template on behalf of an institution, we recommend that you assign the institution as creator rather than an individual. For example, if a staff member at the American Antiquarian Society made a template for a collection, the creator should be "American Antiquarian Society."
* **Description**: A short one- or two-sentence statement about the purpose of the template would be useful here; for example, if it is targeted at a particular collection, you could record which collection or collections would work best with the template.

Once you have filled out all the appropriate fields, click _Create_.

## Creating new fields in your template

Now that you have the metadata about your template, you can create fields in your template.

Tropy currently only allows fields that have URIs in an existing metadata schema. This means that if you have no familiarity with metadata schemas, you are much better off working with an existing template rather than trying to create your own from scratch.

![](../.gitbook/assets/template-fields-2x.png)

* **Property**: The drop-down box here allows you to select from a list of properties that appear in various metadata schemas. The Dublin core fields are the default; you can add other metadata schemas in the [Vocabulary](vocabularies.md) section in Preferences.
  * You can search for metadata terms by clicking in the Property field and starting to type a term. Click on the term that you want.
  * The Property name is what will appear in your template. If you want it to read something different \(for example, "Source" renamed to "Archive"\), you can fill in the Label field with your desired label.
* **Is mandatory field**: If this box is checked, Tropy will post an alert button next to the field in the metadata pane in the project or item view of Tropy until it is properly filled in.
* **Hint**: The hint will appear in the editable field of the metadata template in the project or item view. The hint is a useful way to remind yourself of what you meant by the property you selected. For example, if you are using a standard format such as ISO for dates, you could put "ISO format" in the hint. 
* **Default value**: If this box is filled in, the text in the box will appear automatically in the metadata pane in the project or item view. This feature is especially relevant for institutions creating templates for patrons to use. You can fill in, for example, the name of your institution, as you wish it to appear, the rights information attached to your collections, and other fields that will be the same no matter who uses the template. 
  * **Is read-only**: This box, only clickable if a default value is set, allows the creator of a template to indicate that the default value cannot be changed within the metadata pane.

To add more fields to your template, click on the + on the right-hand side. To delete fields, click on the -.

You can re-order your fields by dragging their boxes. Click and hold on the left-hand side of the box to place your fields in a different order.

