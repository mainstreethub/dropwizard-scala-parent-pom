import com.mainstreethub.jenkins.pipelines.Notifier
import com.mainstreethub.jenkins.pipelines.java.library.Pipeline

def notifier = new Notifier([
  steps: this,
  ownerChannels: ["data-team-notif"]
])

new Pipeline(this)
  .run([
    notifier: notifier,
    isOpenSource: true
  ])
