## TIL: 27-07-2021
**IntelliJ Handy Shortcuts**
* Bookmark files/lines on your IDE<br>
  * To add/remove a bookmark to a file press `Ctrl+Shift+F11` key.
  * To view all your bookmarked files press `Shift+F11`.
* Recently opened/edited files: `Ctrl+E`
* Find in Files: `Ctrl+H`
* Choose the content to Paste: `Ctrl+Shift+V`

**Docker Caching - To avoid invalidating the cache**<br>
**Steps:**
 1. Start your Dockerfile with commands that are less likely to change
 2. Place commands that are more likely to change (like COPY . .) as late as possible
 3. Add only the necessary files (use a .dockerignore file)

## TIL: 02-08-2021
- Learnt about remote debugging Java applications running on Kubernetes cluster
- Get the IP of any node present on cluster: `kubectl get nodes --selector=owner=<owner> -o wide`
- Get the debug port of service: `kubectl -n <namespace> get svc <service_name>`
- Learnt about hot swapping java code on remote host

## TIL: 06-08-2021
- Application performance can be improved by compressing JSON using gzip. It will reduce the JSON size by 75%. Which eventually improves API turnaround time significantly.
- Instead of using simple JSON library, you can use minidev JSON library which is better in performance.
- You can generate mock data in bulk from this website: https://www.mockaroo.com/

## TIL: 12-08-2021
- If your organisation used Jira and Gitlab, you should enable smart commits on Gitlab integration settings. It will automatically link every commit to corresponding Jira ticket.


