# Connector Name: Partoo Presence & Review Analytics

## Description
The Partoo Presence & Review Analytics Connector is a powerful tool designed to empower Partoo's clients with insightful data analytics for managing and improving their online presence and reviews. This Looker Studio Connector seamlessly integrates with Partoo's platform to provide users with an automated and user-friendly way to visualize and understand their online presence and customer reviews.

## Key Features
1. **Automated Data Retrieval**: The connector automates the retrieval of crucial data related to your business's online presence, including business listings, customer reviews, ratings, and more.
2. **Customizable Dashboards**: Easily create and customize analytics dashboards tailored to your specific business needs. Visualize data trends, track performance metrics, and gain valuable insights into your online presence management.
3. **Top Keywords**: Gain a comprehensive view of your business's top 50 keywords on Google My Business, and more.
4. **Mobile & Desktop Impression Tracking**: Monitor and analyze impressions of your Google Business Profile on both mobile and desktop devices. Understand where your audience is engaging with your business and optimize your presence accordingly.
5. **Time-Based Analytics**: Analyze data trends over time, allowing you to make data-driven decisions and adapt your online presence and review management strategies as needed.
6. **User-Friendly Interface**: The Looker Studio Connector offers an intuitive and user-friendly interface that empowers users of all levels to access and interpret data effortlessly.
7. **Collaborative Environment**: Foster collaboration among team members by sharing dashboards, reports, and insights to make informed decisions together.

## Benefits
- **Data-Driven Decision Making**: Make informed decisions based on real-time data insights to enhance your online presence and reputation management strategies.
- **Improved Customer Satisfaction**: Identify areas for improvement and enhance customer satisfaction through data-driven actions.
- **Competitive Edge**: Stay ahead of competitors by benchmarking your performance and strategically adapting your online presence management.
- **Time and Resource Efficiency**: Automate data gathering and reporting, saving valuable time and resources while increasing productivity.

## Get Started Today
Empower your business with the Partoo Presence & Review Analytics Connector and gain a competitive edge in managing your online presence and reviews. Make data-driven decisions that lead to enhanced customer satisfaction and business growth.


# Fields Description

## General
- **group_list** (STRUCT): Groups are used as a filtering system, either to filter businesses by group. 
- **section_list** (STRUCT): To facilitate filtering, groups are now gathered into Sections.
## Reviews Data Fields
- **review_year_month** (DATE): Year and month of the review.
- **review_business_id** (STRING): Unique identifier for the reviewed business.
- **org_id** (INTEGER): Unique ID for the organization associated with the review.
- **review_org_name** (STRING): Name of the organization associated with the review.
- **review_organization_type** (STRING): Type of the organization (e.g., restaurant, retail).
- **review_provider** (STRING): Platform where the review was posted.
- **review_business_name** (STRING): Name of the business being reviewed.
- **review_code** (STRING): Unique code associated with the review.
- **review_country** (STRING): Country of the business being reviewed.
- **review_nb_recommended** (INTEGER): Number of positive acknowledgments.
- **review_partner** (STRING): Partner entity associated with the review.
- **review_reply_template_per_default** (STRING): Default reply template for reviews.
- **review_first_subscription_date** (DATE): First subscription date related to the review.
- **review_subs_review** (STRING): Subscriber's review text.
- **review_nb_with_content** (INTEGER): Number of reviews with substantive content.
- **review_nb_without_content** (INTEGER): Reviews without substantive content.
- **review_nb_business** (INTEGER): Number of businesses reviewed.
- **review_nb_non_negative_date** (INTEGER): Non-negative reviews by date.
- **review_sum_non_negative_day** (FLOAT): Total non-negative reviews over time.
- **review_sum_rating** (INTEGER): Sum of all review ratings.
- **review_answer_rate** (FLOAT): Rate of review responses.
- **review_nb_answer** (INTEGER): Reviews that received an answer.
- **review_nb_answer_for_negative_rating** (INTEGER): Negative reviews that received an answer.
- **nb_review** (INTEGER): Total number of reviews.
- **review_nb_negative_rating** (INTEGER): Number of negative ratings.
- **review_sum_negative_rating** (INTEGER): Sum of negative ratings.
- **review_nb_treated** (INTEGER): Number of addressed reviews.
- **review_nb_review_with_positive_time** (INTEGER): Reviews with positive response time.

## Keywords Data Fields
- **keyword_group_list** (REPEATED STRING): List of keyword groups.
- **keyword_business_name** (STRING): Business name associated with the keyword.
- **keyword_business_id** (STRING): Unique business ID for the keyword.
- **keyword_org_name** (STRING): Organization name associated with the keyword.
- **keyword** (STRING): Specific keyword.
- **keyword_count** (INTEGER): Count of the specific keyword.
- **keyword_year_month** (DATE): Year and month for the keyword data.
- **keyword_rank** (INTEGER): Keyword ranking.
- **review_org_id** (INTEGER): Organization ID for the review.
- **keyword_org_id** (INTEGER): Organization ID for the keyword.
- **rank_review_duplicate** (INTEGER): Occurrence of duplicate reviews.
- **daily_metric_year_month** (DATE): Year and month for daily metric data.
- **daily_metric_business_id** (STRING): Business ID for daily metrics.

## Daily Metrics Data Fields
- **daily_metric_org_id** (INTEGER): Organization ID for daily metrics.
- **daily_metric_org_name** (STRING): Organization name for daily metrics.
- **daily_metric_organization_type** (STRING): Type of organization for daily metrics.
- **daily_metric_provider** (STRING): Provider of daily metrics.
- **daily_metric_business_name** (STRING): Business name for daily metrics.
- **daily_metric_code** (STRING): Unique code for daily metrics.
- **daily_metric_country** (STRING): Country for daily metrics.
- **daily_metric_group_list** (REPEATED STRING): Groups associated with daily metrics.
- **daily_metric_section_list** (REPEATED STRING): Sections for daily metrics.
- **daily_metric_group_list_char** (STRING): Group list character string for daily metrics.
- **daily_metric_categories** (STRING): Categories for daily metrics.
- **daily_metric_gcid** (STRING): Google category ID for the business.
- **daily_metric_nb_bm** (INTEGER): Number of business metrics.
- **daily_metric_category** (STRING): Category of the daily metric.
- **daily_metric_industry** (STRING): Industry for daily metrics.
- **daily_metric_sub_industry** (STRING): Sub-industry for daily metrics.
- **daily_metric_business_impressions_desktop_search** (INTEGER): Desktop search impressions.
- **daily_metric_business_impressions_mobile_search** (INTEGER): Mobile search impressions.
- **daily_metric_business_impressions_desktop_maps** (INTEGER): Desktop maps impressions.
- **daily_metric_business_impressions_mobile_maps** (INTEGER): Mobile maps impressions.
- **daily_metric_business_conversations** (INTEGER): Business-related conversations.
- **daily_metric_business_bookings** (INTEGER): Business bookings.
- **daily_metric_business_food_orders** (INTEGER): Food orders for the business.
- **daily_metric_call_clicks** (INTEGER): Call clicks from business listing.
- **daily_metric_website_clicks** (INTEGER): Clicks to business's website.
- **daily_metric_business_direction_requests** (INTEGER): Direction requests to the business.
- **rank_kw_duplicate** (INTEGER): Occurrence of duplicate keywords.
- **rank_dm_duplicate** (INTEGER): Occurrence of duplicate daily metrics.
- **business_id** (STRING): Unique business identifier.
- **provider** (STRING): Service provider or platform.
- **country** (STRING): Country of the business.
- **business_name** (STRING): Name of the business.  

[Partoo](https://www.partoo.co/en/)  
[Privacy policy](PRIVACY.md)  
[Terms of service](TOS.md)  
