# GCP service accounts

These service accounts are generated automatically when you use (i.e., enable) a GCP service like Cloud Functions, Cloud Run, or Cloud Storage to name a few.

Here's a list (not complete) of these Google-managed service accounts I've come across. 

| Service | Service account | Role |
|---|---|---|
| AI Platform | service-PROJECT_NUMBER@cloud-ml.google.com.iam.gserviceaccount.com | Cloud ML Service Agent |
| AutoML | service-PROJECT_NUMBER@gcp-sa-automl.iam.gserviceaccount.com | AutoML Service Agent |
| Cloud APIs | PROJECT_NUMBER@cloudservices.gserviceaccount.com | Editor |
| Cloud Build | service-PROJECT_NUMBER@gcp-sa-cloudbuild.iam.gserviceaccount.com | Cloud Build Service Agent |
| Cloud Build | PROJECT_NUMBER@cloudbuild.gserviceaccount.com | Cloud Build Service Account |
| Cloud Functions | service-PROJECT_NUMBER@gcf-admin-robot.iam.gserviceaccount.com | Cloud Functions Service Agent |
| Cloud Run | service-PROJECT_NUMBER@serverless-robot-prod.iam.gserviceaccount.com | Cloud Run Service Agent |
| Cloud Scheduler | service-PROJECT_NUMBER@gcp-sa-cloudscheduler.iam.gserviceaccount.com | Cloud Scheduler Service Agent |
| Cloud Tasks | service-PROJECT_NUMBER@gcp-sa-cloudtasks.iam.gserviceaccount.com | Cloud Tasks Service Agent |
| Compute Engine | service-PROJECT_NUMBER@compute-system.iam.gserviceaccount.com | Compute Engine Service Agent |
| Container Registry | service-PROJECT_NUMBER@containerregistry.iam.gserviceaccount.com | Editor |
| Dataprep | service-PROJECT_NUMBER@trifacta-gcloud-prod.iam.gserviceaccount.com | Dataprep Service Agent |
| Data Fusion | service-PROJECT_NUMBER@gcp-sa-datafusion.iam.gserviceaccount.com | Cloud Data Fusion API Service Agent |
| Data Loss Prevention | service-PROJECT_NUMBER@dlp-api.iam.gserviceaccount.com | DLP API Service Agent |
| Data Labeling | service-PROJECT_NUMBER@gcp-sa-datalabeling.iam.gserviceaccount.com | DataLabeling Service Agent |
| Dataflow | service-PROJECT_NUMBER@dataflow-service-producer-prod.iam.gserviceaccount.com | Cloud Dataflow Service Agent |
| Dataproc | service-PROJECT_NUMBER@dataproc-accounts.iam.gserviceaccount.com | Dataproc Service Agent |
| Endpoints | service-PROJECT_NUMBER@endpoints-portal.iam.gserviceaccount.com | Endpoints Portal Service Agent |
| Filestore | service-PROJECT_NUMBER@cloud-filer.iam.gserviceaccount.com | Cloud Filestore Service Agent |
| Firebase | firebase-service-account@firebase-sa-management.iam.gserviceaccount.com | Firebase Service Management Service Agent |
| Firestore/Datastore | service-PROJECT_NUMBER@firebase-rules.iam.gserviceaccount.com	| Firebase Rules System |
| Healthcare | service-PROJECT_NUMBER@gcp-sa-healthcare.iam.gserviceaccount.com | Healthcare Service Agent |
| IoT Core | service-PROJECT_NUMBER@gcp-sa-cloudiot.iam.gserviceaccount.com | Cloud IoT Core Service Agent |
| KMS | - | - |
| Kubernetes Engine | service-PROJECT_NUMBER@container-engine-robot.iam.gserviceaccount.com | Kubernetes Engine Service Agent |
| Memorystore | service-PROJECT_NUMBER@cloud-redis.iam.gserviceaccount.com | Cloud Memorystore Redis Service Agent |
| Pub/Sub | service-PROJECT_NUMBER@gcp-sa-pubsub.iam.gserviceaccount.com | Service Account Token Creator |
| Source Repositories | service-PROJECT_NUMBER@sourcerepo-service-accounts.iam.gserviceaccount.com | Cloud Source Repositories Service Agent |
| Storage | service-PROJECT_NUMBER@gs-project-accounts.iam.gserviceaccount.com |  |
| Spanner | - | - |
| Web Security Scanner | service-PROJECT_NUMBER@gcp-sa-websecrutiyscanner.iam.gserviceaccount.com | Cloud Web Security Scanner Service Agent |
