# Docker Composeファイルを使用してフロントエンドを実行
docker_compose('compose.yml')
docker_build('app:v0.0.0', '.', dockerfile='./containers/frontend/Dockerfile')
docker_prune_settings( disable = False, max_age_mins = 0, num_builds = 1, keep_recent = 0 )
