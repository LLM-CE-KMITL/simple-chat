# simple-chat
Simple App of chat with LLM studio

## Enable OpenAPI with CORS in LLM Studio (UI)

1. **Open LLM Studio UI**  
   Navigate to your LLM Studio web interface in your browser.

2. **Go to Settings → API**  
   In the left sidebar, click on **Developer** settings.

3. **Running Server**  
   Toggle **"Running"** to **ON**.

4. **Enable CORS**  
   Find a button **"Settings"**.
   Then, toggle **"Enable CORS"** to **ON**  
   This allows external web apps (e.g., from `localhost`) to connect.

5. **Copy API**
   The URL might be http://192.168.1.102:1234/v1/chat/completions

### Note 
Try changing the content in  
`[{role:'system', content:'You are a useful assistant.'}]`
to serve your assistant role.
