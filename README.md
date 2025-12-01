<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OGL Chat Bot</title>
    
    <link rel="stylesheet" href="https://www.gstatic.com/dialogflow-console/fast/df-messenger/prod/v1/themes/df-messenger-default.css">

    <style>
        /* 1. Reset Body */
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            width: 100%;
            background-color: #fff; /* Ensure white background */
        }

        /* 2. Style the Container to Fill Screen */
        df-messenger {
            z-index: 999;
            position: fixed;
            bottom: 0;
            right: 0;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            
            /* CSS Variables to control colors */
            --df-messenger-font-color: #000;
            --df-messenger-font-family: Google Sans;
            --df-messenger-chat-background: #f3f6fc;
            --df-messenger-message-user-background: #d3e3fd;
            --df-messenger-message-bot-background: #fff;
        }

        /* 3. Hide Citations */
        df-accordion { display: none !important; }
        .df-citation-list { display: none !important; }
    </style>
</head>
<body>
    <!-- <iframe
    src="https://storage.googleapis.com/ogl-chat-public-host/chat-bot.html"
    width="400"
    height="600"
    style="border: none; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.15); position: fixed; bottom: 20px; right: 20px; z-index: 9999;"
    title="OGL Assistant">
</iframe> -->

    <script src="https://www.gstatic.com/dialogflow-console/fast/df-messenger/prod/v1/df-messenger.js"></script>

    <df-messenger
        project-id="agent-builder-479506"
        agent-id="11aa8e4e-420f-4a8a-a894-d8f1761bd438"
        language-code="en"
        max-query-length="-1">
        
        <df-messenger-chat
            chat-title="OGL Assistant">
        </df-messenger-chat>

    </df-messenger>

</body>
</html>
