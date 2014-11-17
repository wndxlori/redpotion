![image](http://ir_wp.s3.amazonaws.com/wp-content/uploads/sites/11/2014/11/logo_02.png)

# RedPotion

*Note the potion command isn't working yet. It will soon*


RedPotion combines [RMQ](http://rubymotionquery.com/), [ProMotion](https://github.com/clearsightstudio/ProMotion), [CDQ](https://github.com/infinitered/cdq), [AFMotion](https://github.com/clayallsopp/afmotion), and other libraries. It also adds new features to better integrate RMQ with ProMotion.

Its goals are to choose standard libraries and promote best practices, allowing you to developed iOS apps in record time.

=========

The **makers of RMQ** at [InfiniteRed](http://infinitered.com/) and the **creators of ProMotion** at [ClearSight Studio](https://clearsightstudio.com/) have teamed up to create the ultimate RubyMotion library.

[![image](https://ir_wp.s3.amazonaws.com/wp-content/uploads/sites/11/2013/08/InfiniteRed_logo_100h.png)](http://infinitered.com/) &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [![image](https://clearsightstudio.com/assets/images/clearsight-logos/color-logo@2x-458a9655.png)](https://clearsightstudio.com/)

ProMotion for screens and RMQ for styles, animations, traversing, events, etc.

## Plugins and Add-ons

You can use both RMQ Plugins and ProMotion Add-ons

![image](https://camo.githubusercontent.com/523372b371be1de2fb2cec421be423e2b89bcfd0/687474703a2f2f69725f77702e73332e616d617a6f6e6177732e636f6d2f77702d636f6e74656e742f75706c6f6164732f73697465732f31392f323031342f30392f726d715f706c7567696e2e706e67)  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ![image](http://ir_wp.s3.amazonaws.com/wp-content/uploads/sites/11/2014/11/ProMotion-addon-logo.png)

ProMotion Addon

## Quick start

```
gem install red_potion

potion create my_app
bundle
rake pod:install
potion create model state
potion create table_screen states
 # a few changes
rake
```

![image](http://ir_wp.s3.amazonaws.com/wp-content/uploads/sites/11/2014/11/pm_table.png)

## Contributing

1. Fork it
2. Create your feature branch (`git checkoutut -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request