# testing-slot
This is a sample python application that shows the promotion of artifacts from the build stage to the final deployment
environment. Within this pipeline, we have several environments that mimics our environment. The following environment
are divided into two subscriptions - Non-prod and prod
Each subscription has a service (Azure Webapp) that is divided into two environments (default deployment slot and final deployment slot)
This pipeline accounts for different attributes like cacheing, environment manual required approval, ITSM integration, A&B deployment strategy with traffic quota sharing of 30% at the initial slot.
