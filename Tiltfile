# Docker Composeファイルを使用してフロントエンドを実行
docker_compose('compose.yml')
docker_build('app:v0.0.0', '.', dockerfile='./containers/frontend/Dockerfile')

# バグの再現。max_age_mins は1以上でないと動かない。
docker_prune_settings( disable = False, max_age_mins = 0, num_builds = 1, keep_recent = 0 )
