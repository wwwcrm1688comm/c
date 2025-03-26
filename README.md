import matplotlib.pyplot as plt
import seaborn as sns

# 结果可视化示例：绘制散点图
def plot_scatter(df, x_column, y_column):
    plt.figure(figsize=(10, 6))
    sns.scatterplot(data=df, x=x_column, y=y_column)
    plt.title(f'Scatter Plot of {x_column} vs {y_column}')
    plt.xlabel(x_column)
    plt.ylabel(y_column)
    plt.show()
