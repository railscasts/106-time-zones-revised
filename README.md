# RailsCasts Episode #106: Time Zones (revised)

http://railscasts.com/episodes/106-time-zones-revised

Requires Ruby 1.9.2 or higher.


### Commands used in this episode

```
rails g migration add_time_zone_to_users time_zone
rake db:migrate
```


### Commands used in rails console

```ruby
h = Haiku.last
h.published_at
h.published_at_before_type_cast
Time.now
Time.zone.now
Time.now.class
Time.zone.now.class
Time.now.in_time_zone
Date.today
Date.current
Time.zone.now.to_date
Time.zone.parse("Jan 1, 2010")
4.weeks.ago
```
