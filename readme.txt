=== Add Meta Tags ===
Contributors: gnotaras
Donate link: http://bit.ly/HvUakt
Tags: amt, meta, metadata, seo, optimize, ranking, description, keywords, metatag, schema, opengraph, dublin core, schema.org, microdata, google, twitter cards, google plus, yahoo, bing, search engine optimization, rich snippets, semantic, structured, meta tags, product, woocommerce, edd, breadcrumbs, breadcrumb trail
Requires at least: 3.1.0
Tested up to: 4.2
Stable tag: 2.8.8
License: Apache License v2
License URI: http://www.apache.org/licenses/LICENSE-2.0.txt

Add basic meta tags and also Opengraph, Schema.org Microdata, Twitter Cards and Dublin Core metadata to optimize your web site for better SEO.


== Description ==

*Add-Meta-Tags* (<abbr title="Add-Meta-Tags Wordpress plugin">AMT</abbr>) adds metadata to your content, including the basic *description* and *keywords* meta tags, [Opengraph](http://ogp.me "Opengraph specification"), [Schema.org](http://schema.org/ "Schema.org Specification"), [Twitter Cards](https://dev.twitter.com/docs/cards "Twitter Cards Specification") and [Dublin Core](http://dublincore.org "Dublin Core Metadata Initiative") metadata.

It is actively maintained since 2006 (historical [Add-Meta-Tags home](http://www.g-loaded.eu/2006/01/05/add-meta-tags-wordpress-plugin/ "Official historical Add-Meta-Tags Homepage")).

*Add-Meta-Tags* is one of the personal software projects of George Notaras. It is developed in his free time and released to the open source WordPress community as Free software.


= Highlights of the latest releases =

- Since v2.8.7 a template tag for the generation of a *semantic breadcrumb trail* is available for use in your themes (see below for more info).
- Since v2.8.1 Add-Meta-Tags supports the generation of metadata for *product* and *product group* pages for the *WooCommerce* and *Easy-Digital-Downloads* e-commerce plugins.


= Goals =

The goals of the Add-Meta-Tags plugin are:

- be a free, yet high quality, metadata extension for the WordPress publishing platform.
- provide efficient, out-of-the-box search engine optimization (*SEO*).
- be customizable, yet simple and easy to use and configure, with minimal or no support.
- be as lightweight as possible.
- support advanced customization through the WordPress filter/action system (for developers and advanced users).


= Free License and Donations =

*Add-Meta-Tags* is released under the terms of the <a href="http://www.apache.org/licenses/LICENSE-2.0.html">Apache License version 2</a> and, therefore, is **Free software**.

However, a significant amount of **time** and **energy** has been put into developing this plugin, so, its production has not been free from cost. If you find this plugin useful and if it has helped your blog get indexed better and rank higher, you can show your appreciation by making a small <a href="http://bit.ly/HvUakt">donation</a>.

Donations in the following crypto currencies are also accepted and welcome. Send coins to the following addresses:

- BitCoin (BTC): `1KkgpmaBKqQVk643VRhFRkL19Bbci4Mwn9`

Thank you in advance for **donating**!


= What it does =

*Add-Meta-Tags* (referred to as *AMT* hereafter) adds metadata to your web site. This metadata contains information about the **content**, the **author**, the **publisher**, the **media files**, which have been attached to your content, and even about some of the **embedded media** (see the details about this feature in the relevant section below).

*Metadata* refers to information that describes the content in a machine-friendly way. Search engines and other online services use this metadata to better understand your content. Keep in mind that metadata itself neither automatically makes your blog rank better nor makes your content more useful. For this to happen the content is still required to meet various quality standards. However, the presence of accurate and adequate metadata gives search engines and other services the chance to make less guesses about your content, index and categorize it better and, eventually, deliver it to an audience that finds it useful. Good metadata facilitates this process and thus plays a significant role in achieving better rankings. This is what the *Add-Meta-Tags* plugin does.


= Features =

Add-Meta-Tags automatically generates metadata for your content.

**Main Features**

The main features of the plugin include:

* Generation of basic meta tags, such as the *description* and *keywords* meta tags.
* Generation of [Opengraph](http://ogp.me "Opengraph specification") metadata.
* Generation of [Schema.org](http://schema.org/ "Schema.org Specification") metadata.
* Generation of [Twitter Cards](https://dev.twitter.com/docs/cards "Twitter Cards Specification") metadata.
* Generation of [Dublin Core](http://dublincore.org "Dublin Core Metadata Initiative") metadata.
* The various metadata types are generated for posts, pages, custom post types, attachment pages, category, tag, custom-taxonomy, author archives and the front page. Please note that not all generators produce metadata for all the aforementioned content types. In some cases, this happens because of limitations of the metadata specification. Moreover, the generators are constantly being improved so as to produce as complete metadata as possible.
* Supports both the default 'latest posts' front page or static pages, which are used as the front page and as the 'latest posts' page.
* Supports the generation of metadata for some types of embedded media (see below for more information).
* Supports the generation of metadata for *product* and *product group* pages for the *WooCommerce* and *Easy-Digital-Downloads* e-commerce plugins. (This featured is marked as `Work-In-Progress`)
* The metadata generators support social media profile links for each author.
* Publisher settings shared by all authors (currently only social media profile links).
* Custom locale setting, which is used in all generated metadata.

**Additional Features**

Additional SEO and other features include:

* Web site description and keywords.
* Global keywords. These are keywords that are automatically added to the keywords of the content throughout the web site.
* Site-wide meta tags. It is possible to add full meta tags, such as verification meta tags or meta tags with extra robots rules, that appear throughout the web site.
* Supports a default image, such as your web site's logo, which is used as a fallback, if no other image can be determined.
* Supports the addition of the *copyright* meta tag.
* Supports the addition of the `NOODP,NOYDIR` options to the *robots* meta tag.
* Supports the addition of the `NOINDEX,FOLLOW` options to the *robots* meta tag on category, tag, author, time based archives and search results. The option to exclude the first page of each of the aforementioned archives from this rule is provided.
* Metadata review mode. When enabled, WordPress users with administrator privileges see a box (right above the post's content) containing the metadata exactly as it is added in the HTML head and body for easier examination. The box is displayed on posts, pages, attachments and custom post types.
* Supports reading data, such as custom descriptions, keywords, custom titles, etc from external fields and thus makes the migration from other plugins extremely easy.

**Customization through the User Interface**

The generation of metadata is automatic. However, customization by the user is possible directly from the [post editing screen](https://en.support.wordpress.com/posts/post-screen/). Add-Meta-Tags adds a metabox in this screen, the `Metadata` box, which offers the following metadata customization features:

* Custom description.
* Custom keywords.
* Custom content of the `<title>` element.
* News keywords. ([read more](http://support.google.com/news/publisher/bin/answer.py?hl=en&answer=68297))
* Full meta tags box, which can be used to enter full meta tags (`<meta>` and `<link>` elements are allowed by default), which are specific to the post.
* Global image override field, which accepts an image URL, which, if set, overrides the generation of the metadata for any other media file that has been attached to the post.
* Express review, which adds a field that accepts review related information using special notation, which results in the generation of a [Review](http://schema.org/Review) schema.org entity instead of [Article](http://schema.org/Article). This feature is experimental and should be used only by advanced users for testing.
* Referenced items. (Note: Using this very experimental feature is not recommended.)

**Advanced Customization**

Add-Meta-Tags supports advanced customization via the WordPress filter and action system. See the [list of available filter and action hooks](http://www.codetrax.org/projects/wp-add-meta-tags/wiki/Filter_and_Action_Hooks) offered by the plugin.

Although this level of customization is mainly available for developers and power users, much sample code that *just works* can be found in the [forums](https://wordpress.org/support/plugin/add-meta-tags).

Moreover, the [Add-Meta-Tags Cookbook](http://www.codetrax.org/projects/wp-add-meta-tags/wiki/Add-Meta-Tags_Cookbook), which is a collection of code snippets that perform specific commonly needed customizations, is also available. (Note: still work in progress -- needs much work).


= Migrate to Add-Meta-Tags =

Migrating to Add-Meta-Tags from any other plugin is extremely easy. In fact, if the 3rd party plugin stores data in [Custom Fields](https://codex.wordpress.org/Custom_Fields) provided by WordPress, no migration process needs to be done. Add-Meta-Tags can read data from multiple external fields by adding a small snippet of PHP code in the `functions.php` file of your theme.

So, if you decided to use Add-Meta-Tags as you main SEO plugin or if you just want to test how it would work with the data you have inserted in another plugin, please check the [Migrating to Add-Meta-Tags](http://www.codetrax.org/projects/wp-add-meta-tags/wiki/Migrate_to_Add-Meta-Tags) section of the Add-Meta-Tags Cookbook.


= Key Notes about the Metadata Generators =

This section contains some detals about the available metadata generators. More information for each generator can be found in the plugin settings page.

**Opengraph metadata**

Opengraph meta tags can be automatically added to the front page, posts, pages, custom post types, attachment pages and author archive.

It is possible to control the value of the `og:type` meta tag either by changing the post format or programmatically via a filter. By default, the `og:type` is set to `article` for all content, except for video attachment pages and posts whose post format has been set to `video`, on which `og:type` is set to `video.other`.

**Schema.org Microdata**

Schema.org Microdata can be automatically added to the front page, posts, pages, custom post types, attachment pages and author archive.

The plugin automatically marks up posts, pages and custom post types as `Article` objects and also images, videos and audio as `Image`, `Video` and `Audio` MediaObjects respectively. It also considers the web site as an `Organization` object and the author as a `Person` object.

**Twitter Cards**

Twitter Cards can be automatically generated for content and attachment pages. The type of card that is generated depends either on the post format or the mime type of the attachment. More specifically:

- A `summary` card is generated for posts with one of the `standard`, `aside`, `link`, `quote`, `status` and `chat` formats.
- A `summary_large_image` card is generated for posts with the `image` format. An image is expected to be attached or embedded to the post.
- A `gallery` card is generated for posts with the `gallery` format. At least one image is expected to be attached or embedded to the post.
- A `photo` card is generated for image attachment pages.
- A `player` card is generated for posts with the `audio` or `video` format and for audio or video attachment pages. Regarding posts, an audio or video is expected to be attached or embedded to the post.

The generation of a `player` card that renders a player for locally hosted audio and video files has very specific requirements, as outlined in the [Player Card specifications](https://dev.twitter.com/cards/types/player). This is why there is a separate option in the plugin configuration panel that enables this feature. In short, enable this feature only if access over the secure HTTPS protocol (SSL) has been configured for your web site, otherwise the Player cards will not be rendered by Twitter.

Moreover, in order to generate the `twitter:image` meta tag of the Player Card of locally hosted audio and video files, it is required to set a featured image on the attachment or on the parent post. By default, Add-Meta-Tags uses the `full` size of the image for the generation of the `twitter:image` meta tag. Advanced users can use the `amt_image_video_preview` filter to customize this image size (see [examples](http://www.codetrax.org/projects/wp-add-meta-tags/wiki/Add-Meta-Tags_Cookbook) about how to use the available filters).

**Dublin Core metadata**

Dublin Core metatags can be automatically added to posts, pages, custom post types and attachment pages.


= Metadata for embedded media =

Add-Meta-Tags generates detailed metadata for the media that have been attached to the content. This happens for all the media you manage in the WordPress media library.

Apart from attaching local media to the content, WordPress lets authors also <a href="http://codex.wordpress.org/Embeds">embed external media</a> by simply adding a link to those media inside the content or by using the `[embed]` shortcode. Several external services are supported.

Add-Meta-Tags can detect some of those media and generate metadata for them. Currently, only links to Youtube, Vimeo and Vine videos, Soundcloud tracks and Flickr images are supported. So, even if you host your media externally on those services, this plugin can still generate metadata for them. This metadata is by no means as detailed as the metadata that is generated for local media, but it gives search engines a good idea about what external media are associated with your content.

This feature relies entirely on the data WordPress has already cached for the embedded media. The plugin will never send any requests to external services attempting to get more detailed information about the embedded media as this would involve unacceptable overhead.

Here is what is supported:

- Links to Youtube videos of the form: `http://www.youtube.com/watch?v=VIDEO_ID`
- Links to Vimeo videos of the form: `http://vimeo.com/VIDEO_ID`
- Links to Vine videos of the form: `https://vine.co/v/VIDEO_ID`
- Links to Soundcloud tracks of the form: `https://soundcloud.com/USER_ID/TRACK_ID`
- Links to Flickr images of the form: `http://www.flickr.com/photos/USER_ID/IMAGE_ID/`

This feature should be considered experimental. This information might be changed in future versions of the plugin.


= Metadata for products =

Add-Meta-Tags, since v2.8.0, supports the generation of OpenGraph, Schema.org and Twitter Cards metadata for products. Please check [example 12](http://www.codetrax.org/projects/wp-add-meta-tags/wiki/Add-Meta-Tags_Cookbook#Example-12-Generate-product-specific-metadata) for more information about how to make Add-Meta-Tags detect your product and product group pages.

Moreover, since v2.8.1 internal support for the *WooCommerce* and *Easy-Digital-Downloads* e-commerce plugins for WordPress is available. By enabling them in the plugin settings page Add-Meta-Tags is able to autodetect the product and product group pages and generate OpenGraph, Schema.org and Twitter Cards metadata. Please check examples [13](http://www.codetrax.org/projects/wp-add-meta-tags/wiki/Add-Meta-Tags_Cookbook#Example-13-Customize-metadata-for-WooCommerce-products) & [14](http://www.codetrax.org/projects/wp-add-meta-tags/wiki/Add-Meta-Tags_Cookbook#Example-14-Customize-metadata-for-Easy-Digital-Downloads-products) for more information about how to customize the metadata that is generated for WooCommerce and EDD products.


= Semantic Breadcrumbs =

Since v2.8.7 a template tag (`amt_breadcrumbs()`) for the generation of a **semantic breadcrumb trail** (Schema.org enhanced) is available for use in your themes.

Below is an example about how to use the template tag in your theme templates to generate a list of Schema.org microdata enabled breadcrumbs for WordPress Pages:

`
<?php
  if ( is_page() && function_exists('amt_breadcrumbs') ) {
    amt_breadcrumbs( array(
      // ID of list element.
      'list_id' => 'breadcrumbs',
      // Show breadcrumb item for the home page.
      'show_home' => true,
      // Text for the home link (requires show_home=true).
      'home_link_text' => 'Home',
      // Show breadcrumb item for the last page.
      'show_last' => true,
      // Show last breadcrumb as link (requires show_last=true).
      'show_last_as_link' => true,
      // Separator. Set to empty string for no separator.
      'separator' => '>'
  )); }
?>
`

The `amt_breadcrumbs()` template tag generates a HTML unordered list. By default, the ID attribute of the list is `breadcrumbs` or whatever you have set in the `list_id` option of the template tag (see above).

The following is entirely optional and not required in order to have semantic breadrumbs.

In order to connect the `breadcrumbs` Schema.org object to the web page's main Schema.org object which represents your content, the following manual actions are necessary:

1. By default, the main Schema.org object that is autogenerated by Add-Meta-Tags for your content is the [Article](http://schema.org/Article). Since the `Article` object does not support a [breadcrumb property](http://schema.org/breadcrumb), it is essential to replace it with the [WebPage](http://schema.org/WebPage) object, which supports a hierarchical structure. This can easily be done by adding the following code to your theme's `functions.php`:

`
function amt_schemaorg_set_webpage_entity_on_pages( $default ) {
    if ( is_page() ) {
        return 'WebPage';
    }
    return $default;    // Article
}
add_filter( 'amt_schemaorg_object_main', 'amt_schemaorg_set_webpage_entity_on_pages' );
`

2. Now that the main Schema.org object has been set to [WebPage](http://schema.org/WebPage), we also need to interconnect it with the [BreadcrumbList](http://schema.org/BreadcrumbList) object, which is generated by the `amt_breadcrumbs()` template tag. This can be done by adding the `breadcrumbs` object's ID in the `itemref` attribute of the WebPage object with the following code (again in the `functions.php` file of the theme):

`
function amt_set_itemref() {
    if  ( is_page() ) {
        // Should return space delimited list of entity IDs
        return 'breadcrumbs';
    }
    return '';
}
add_filter( 'amt_schemaorg_itemref_content', 'amt_set_itemref' );
`

Now your semantic breadcrumbs have been connected to the main Schema.org object (WebPage).

In case you use code that generates other Schema.org objects throughout the web page, you can connect those objects to the main Schema.org object by attaching a filtering function like `amt_set_itemref` to the `amt_schemaorg_itemref_content` hook. The function must return a space delimited list of IDs.

= Translations =

There is an ongoing effort to translate Add-Meta-Tags to as many languages as possible. The easiest way to contribute translations is to register to the [translations project](https://www.transifex.com/projects/p/add-meta-tags "Add-Meta-Tags translations project") at the Transifex service.

Once registered, join the team of the language translation you wish to contribute to. If a team does not exist for your language, be the first to create a translation team by requesting the language and start translating.


= Code Contributions =

If you are interested in contributing code to this project, please make sure you read the [special section](http://wordpress.org/plugins/add-meta-tags/other_notes/#How-to-contribute-code "How to contribute code") for this purpose, which contains all the details.


= Support and Feedback =

Please post your questions and provide general feedback and requests at the [Add-Meta-Tags Community Support Forum](http://wordpress.org/support/plugin/add-meta-tags).

To avoid duplicate effort, please do some research on the forum before asking a question, just in case the same or similar question has already been answered.

Also, make sure you read the [FAQ](http://wordpress.org/plugins/add-meta-tags/faq/ "Add-Meta-Tags FAQ").


= Template Tags =

The following *template tags* are available for use in your theme:

1. `amt_content_description()` : prints the content's description as generated by Add-Meta-Tags.
1. `amt_content_keywords()` : prints a comma-delimited list of the content's keywords as generated by Add-Meta-Tags.
1. `amt_metadata_head()` : prints the full metadata for the head area as generated by Add-Meta-Tags.
1. `amt_metadata_footer()` : prints the full metadata for the head area as generated by Add-Meta-Tags.
1. `amt_breadcrumbs()` : prints an unordered list of semantic (Schema.org enabled) breadcrumbs.


**More**
 
Check out other [open source software](http://www.codetrax.org/projects) by George Notaras.


== Installation ==

Add-Meta-Tags can be easily installed through the plugin management interface from within the WordPress administration panel (*recommended*).

Alternatively, you may manually extract the compressed (zip) package in the `/wp-content/plugins/` directory.

After the plugin has been installed, activate it through the 'Plugins' menu in WordPress.

Finally, visit the plugin's administration panel at `Settings->Metadata` to read the detailed instructions about customizing the generated metatags.

As it has been mentioned, no configuration is required for the plugin to function. It will add meta tags automatically. Full customization is possible though.

Read more information about the [Add-Meta-Tags installation](http://www.g-loaded.eu/2006/01/05/add-meta-tags-wordpress-plugin/ "Official Add-Meta-Tags Homepage").


== Frequently Asked Questions ==

= Plugin X displays a warning about Add-Meta-Tags being incompatible! What should I do? =

Add-Meta-Tags is compatible with every plugin available for WordPress. It never affects the functionality of other plugins in any way.

Please read our <a title="Add-Meta-Tags Compatibility Notice" href="https://wordpress.org/support/topic/compatibility-notice-apr-09-2015">Compatibility Notice</a>. Also, check out our <a href="https://wordpress.org/support/topic/about-the-warnings-issued-by-3rd-party-plugins-for-add-meta-tags-apr-11-2015">message</a> about warnings issued by 3rd parties.

= I see duplicate meta tags in the HTML source! =

Add-Meta-Tags does not generate duplicate meta tags. Moreover, it does not check the HTML head area for duplicate meta tags. This is the responsibility of the user. Please make sure no meta tags are hardcoded into your theme (usually the `header.php` template). Also, if you use multiple SEO plugins, make sure that similar features, eg Twitter Cards metadata, is not enabled in both plugins.

= The blog title appears in the 'title' HTML element even if a custom title has been set! =

Most probably this issue is related to your theme. Please try to reproduce the same behavior using one of the default themes. If it is reproducible, please let me know about it in the forums.

= Metadata validation tools show the error [Error: Missing required field "updated"]! =

This is an issue related to <a title="Microformats Specification" href="http://microformats.org/">Microformats</a> metadata, which is hard-coded into the theme. It is not related to Schema.org microdata and also not related to Add-Meta-Tags.

= My meta tags do not show up! =

Please, check if your theme's `header.php` file contains the following required piece of code: `<?php wp_head(); ?>`. If this is missing, contact the theme author.

= My meta tags show up twice! =

The *description* and *keywords* meta tags are most probably already hardcoded into your theme's `header.php` file. Please contact the theme author.

= I paste HTML code in the 'Full Meta Tags' box, but it keeps disappearing! =

For security reasons, only `<meta>` HTML elements are allowed in this box.

= Where can I get support? =

You can get first class support from the [community of users](http://wordpress.org/support/plugin/add-meta-tags "Add-Meta-Tags Users"). Please post your questions, feature requests and general feedback in the forums.

Keep in mind that in order to get helpful answers and eventually solve any problem you encounter with the plugin, it is essential to provide as much information as possible about the problem and the configuration of the plugin. If you use a customized installation of WordPress, please make sure you provide the general details of your setup.

Also, my email can be found in the `add-meta-tags.php` file. If possible, I'll help. Please note that it may take a while to get back to you.

= I want to request a new feature! =

Please, feel free to post your request in the forums. Please be descriptive! Providing **detailed feedback** about the requested feature is the best way to contribute.

= Is there a bug tracker? =

You can find the bug tracker at the [Add-Meta-Tags Development web site](http://www.codetrax.org/projects/wp-add-meta-tags).

= There is no amount set in the donation form! How much should I donate? =

The amount of the donation is totally up to you. You can think of it like this: Are you happy with the plugin? Do you think it makes your life easier or adds value to your web site? If this is a yes and, if you feel like showing your appreciation, you could imagine buying me a cup of coffee at your favorite Cafe and <a href="http://bit.ly/HvUakt">make a donation</a> accordingly.

= I've added a low star rating in order to motivate you! Why don't you help me or not implement the feature I want? =

Time permitting, the developer generally tries to do his best with providing free support for this plugin.

But, if you try to force that support with a low star rating, it is guaranteed you are not going to get any help. Unfortunately, it's never going to work that way. So, please, do not do it. You are encouraged to provide detailed feedback in the forums and work closely with the dev in order to get problems fixed. Then, feel free to add your review.

= What should I always bare in mind before asking for support? =

This plugin is Free software. It is developed in the author's free time and is offered without support of any kind. However, the developer tries to do his best to offer support for free in these forums.

You are expected to *collaborate* and act as a *contributor*. Detailed feedback is almost always the key for the quick resolution of any issue. Give the developer time to respond. Acting and expressing demands as if you are the customer or as if the developer is your personal assistant or employee is not a good way to ask for support. In fact, there is very little tolerance for such kind of behavior. Please, do not do it. Fixing all potential issues is just a matter of good collaboration.


== Screenshots ==

Screenshots as of v2.4.0

1. Add-Meta-Tags administration interface ( `Options -> Metadata` ).
2. Enable Metadata meta box in the screen options of the post editing panel.
3. Metadata box in the post editing panel.
4. Contact info entries added by Add-Meta-Tags (AMT) in the user profile page.


== Upgrade Notice ==

= 2.9 =

In 2.9 publisher social media profile links can no longer be set in the WordPress user profile page. Please move such information to the `Publisher Settings` section of Add-Meta-Tags settings page (Settings->Metadata).


== Changelog ==

Please check out the changelog of each release by following the links below. You can also check the [roadmap](http://www.codetrax.org/projects/wp-add-meta-tags/roadmap "Add-Meta-Tags Roadmap") regarding future releases of the plugin.

- [2.8.8](http://www.codetrax.org/versions/288)
 - New experimental metabox feature: Express Review (needs to be enabled in the settings). Adds a metabox field which accepts review related information in special notation and generates a schema.org Review instead of Article. Only for advanced users. Feedback is welcome.
- [2.8.7](http://www.codetrax.org/versions/287)
 - DEPRECATION WARNING: In Add-Meta-Tags v2.9 the ability to store Publisher social profile URLs in the user's Profile Page (Publisher related AMT fields) will no longer be enabled by default. It is highly recommended to set the Publisher's social profile URLs in the plugin settings page (Publisher Settings section).
 - FUNCTIONALITY CHANGE: The Schema.org microdata generator has been improved in 2.8.7. It is highly recommended to check your pages using Google's [Structured Data Testing Tool](https://developers.google.com/structured-data/testing-tool/) or the [Structured Data Validator](https://webmaster.yandex.com/microtest.xml) by Yandex. Some important changes can be found in the entries that follow.
 - Social profile links for the `Organization` and `Person` objects are now automatically added as `sameAs` Schema.org properties to the aforementioned objects.
 - The main Schema.org object of the front page has been changed to `WebSite` and the `Organization` object has been added to it as the `publisher` property.
 - Added support for the [Sitelinks Search Box](https://developers.google.com/structured-data/slsb-overview).
 - A new **template tag** that generates a *semantic breadcrumb trail* (contains Schema.org microdata) has been implemented. Please check the description page for more information about how to use the template tag. (props to Nicolaie Szabadkai for ideas and feedback)
 - Added support for the customization (via filter) of the `itemref` attribute of the main Schema.org object. This way other entities, such as a semantic breadcrumb trail or semantic comments/reviews, can be connected to the main Schema.org entity of the web page. Check the information about the breadcrumbs on the description page, which also has all the itemref relevant information.
 - Added [example 16](http://www.codetrax.org/projects/wp-add-meta-tags/wiki/Add-Meta-Tags_Cookbook#Example-16-Extend-the-Organization-properties) to help users add extra social profile links, a postal address and some contact points to the `Organization` object. Make sure you check it out.
- [2.8.6](http://www.codetrax.org/versions/286)
 - Added filter `amt_sanitize_description_extra` filter hook for user-defined description sanitization filtering.
 - Added filter `amt_sanitize_keywords_extra` filter hook for user-defined keywords sanitization filtering.
 - Fixed issue with categories appearing in 'article:tag' Open Graph meta tags. (props to Andrew Arthur Dawson for reporting the issue)
- [2.8.5](http://www.codetrax.org/versions/285)
 - Fixed: term_description() requires the taxonomy slug in order to properly return the term description. (props to pjv for reporting the issue and providing valuable feedback)
 - Auto-detect WooCommerce product group images and use them in the metadata of product group archives.
 - Make it possible to use taxonomy images added by external plugins. See [example 15](http://www.codetrax.org/projects/wp-add-meta-tags/wiki/Add-Meta-Tags_Cookbook#Example-15-Use-external-category-images) about how to actually do it.
- [2.8.4](http://www.codetrax.org/versions/284)
 - Filter hooks for extra Organization/Person related meta tags in the Schema.org generator. (props to Nicolaie Szabadkai for ideas and very useful feedback)
 - Schema.org generator: articleSection should only be set in Article objects. (props to Richard D'Angelo and marketingisa3 for useful feedback)
 - Updated Turkish translation (100%) by BouRock (big thanks).
 - Several other minor bug fixes.
- [2.8.3](http://www.codetrax.org/versions/246)
 - Fixed bug: Post body was not added properly when Schema.org metadata was generated for products. (props to pjv for useful feedback)
- [2.8.2](http://www.codetrax.org/versions/245)
- [2.8.1](http://www.codetrax.org/versions/193)
 - Added new option to omit og:video OpenGraph meta tags. (props to Rika for feedback)
 - Added support for WooCommerce and Easy-Digital-Downloads product and product group page auto-detection. Need to be enabled in the settings. Currently, basic product metadata is generated. Time permitting it will be improved in future releases. Further customization is possible with filtering. See examples [13](http://www.codetrax.org/projects/wp-add-meta-tags/wiki/Add-Meta-Tags_Cookbook#Example-13-Customize-metadata-for-WooCommerce-products) & [14](http://www.codetrax.org/projects/wp-add-meta-tags/wiki/Add-Meta-Tags_Cookbook#Example-14-Customize-metadata-for-Easy-Digital-Downloads-products). (thanks all for feedback)
 - Minor improvements of the README.
 - Updated translations.
- [2.8.0](http://www.codetrax.org/versions/192)
 - Updated the FAQ section.
 - More default image URL adjustments for SSL connections.
 - Improved Schema.org customization via filters. (props to Richard D'Angelo for ideas and feedback)
 - New setting for locale that overrides the WordPress locale setting. (props to eduh12 for ideas and feedback)
 - New metabox feature: global image override. (props to eduh12 for ideas and feedback)
 - Filtering for default Twitter Card type. (props to KV92)
 - Added generic support for products. More info at the description page. (received many requests. too many to mention here. thanks all!)
 - Fixed bug with extra comma in keywords when a post has no categories, no tags, but belongs to a custom taxonomy.
 - Updated translations.

Changelog information for older releases can be found in the ChangeLog file or at the [roadmap](http://www.codetrax.org/projects/wp-add-meta-tags/roadmap "Add-Meta-Tags Roadmap") on the [Add-Meta-Tags development web site](http://www.codetrax.org/projects/wp-add-meta-tags).

