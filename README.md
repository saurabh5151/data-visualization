import seaborn as sns
import matplotlib.pyplot as plt

plt.figure(figsize=(10,6))
top_jobs = df['job_title'].value_counts().head(10)
sns.barplot(y=top_jobs.index, x=top_jobs.values, palette='coolwarm')
plt.title('Top 10 AI Job Titles')
plt.xlabel('Number of Jobs')
plt.ylabel('Job Title')
plt.show()

