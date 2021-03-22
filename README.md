# Hosting now: JS script with custom features for ZOOM Cloud Meetings

[Source repository](https://github.com/edunsouza/zoom-custom-features)

## Features
* Focus on President, Conductor, Reader, Speaker and other default roles
* Create custom focus button
* Delete custom focus button
* Call participant before focus time (open video and mic only, nothing more)
* Comments manager (highlight all hands, open the selected mic and lower others' hands)
* Lower all hands button
* Close all mics from participants with video off
* Participants count (people per device, using pattern: "(# of people) - Name(s)" )
* Naming validation
* Waiting room free pass
* Auto remove spotlights
* Auto request video + mic from participants with "ok" flag on name
* Override default focus buttons' targets
* Status logs (running methods, invalid names, opened videos and mics)
* Send email with participants count (using Vercel serverless functions and Sengrid)
* Turn off all videos and microphones (auto disable the option to allow participant to open its own mic)
* Turn on all videos and microphones (auto enable the option to allow participant to open its own mic)
* Turn on all microphones for claps time (turns off after custom timeout)
