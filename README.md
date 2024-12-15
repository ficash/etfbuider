vfsdfs

git checkout --orphan gh-pages

# 首先，进入 dist 目录
cd dist
 
# 然后，复制所有文件到项目根目录
cp -r * ../

git push origin gh-pages