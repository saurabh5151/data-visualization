plt.figure(figsize=(6,4))
sns.countplot(data=df, x='experience_level', palette='Set2')
plt.title('Experience Level Distribution')
plt.xlabel('Experience Level')
plt.ylabel('Count')
plt.show()

