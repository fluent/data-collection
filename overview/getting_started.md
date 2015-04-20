# Getting Started

Let's get started with [Fluentd](http://www.fluentd.org)!.  [Fluentd](http://www.fluentd.org) is a fully free and fully open-source log collector that instantly enables you to have a '**Log Everything**' architecture with <a href="http://fluentd.org/plugin/">125+ types of systems</a>.

![](/images/fluentd-architecture.png)

Fluentd treats logs as JSON, a popular machine-readable format. It is written primarily in C with a thin-Ruby wrapper that gives users flexibility.

Fluentd's performance has been proven in the field: its largest user currently collects logs from **5000+ servers**, 5 TB of daily data, handling 50,000 msgs/sec at peak time.

## Installing Fluentd

Please follow the installation/quickstart guides below that matches your environment.

* [Install Fluentd by RPM package](install_rpm.md) (Redhat Linux)
* [Install Fluentd by Deb package](install_deb.md) (Ubuntu/Debian Linux)
* [Install Fluentd by DMG package](install_dmg.md) (Apple OSX)
* [Install Fluentd by Ruby Gem](install_ruby_gem.md)
* [Install Fluentd by Chef](install_chef.md)
* [Install Fluentd from source](install_sources.md)

NOTE: Fluentd is currently not supported on Windows. Please see [Windows Data Collection](../use_cases/data_collection_from_Windows.md) for details.

## Usage, examples and others

The articles shown below cover the typical use cases of Fluentd. Please refer to the article(s) that suits your needs.

  * Application Logs
    * [Ruby](../uses_cases/applications/ruby.md), [Python](../uses_cases/applications/python.md), [PHP](../uses_cases/applications/php.md), [Perl](../uses_cases/applications/perl.md), [NodeJS](../uses_cases/applications/nodejs.md), [Java](../uses_cases/applications/java.md), [Scala](../uses_cases/applications/scala.md)
  * Examples
   * [Log Management & Search](../use_cases/log_management_and_search.md) (data search like Splunk)
   * [Log Filtering and Alerting](../use_cases/log_filtering_and_alerting/index.md)
   * [Big Data Analytics with Treasure Data](../use_cases/big_data_analytics.md)
   * [Data Collection to MongoDB](../use_cases/data_collection_to_mongoDB.md)
   * [Data Collection to HDFS](../use_cases/data_collection_to_HDFS.md)
   * [Data Archiving to S3](../use_cases/data_archiving_to_S3.md)
   * [Windows Data Collection](../use_cases/data_collection_from_Windows.md)
  * Basic Configuration
    * [Configuration File](../configuration/configuration_file.md)
  * Happy Users :)
    * [Users](http://www.fluentd.org/testimonials)

## Learn More

The articles shown below will provide detailed information for you to learn more about Fluentd.

  * [Architecture Overview](http://www.fluentd.org/architecture)
  * Plugin Overview
    * [Input Plugins](../input_plugins/index.md)
    * [Output Plugins](../output_plugins/index.md)
    * [Buffer Plugins](../buffer_plugins/index.md)
  * [High Availability](../deployment/high_availability.md)
  * [FAQ](overview/faq.md)
