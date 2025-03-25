deploy:
	hugo
	cd public && \
		rm -rf .git/ && \
		git init . && \
		git remote add origin git@github.com:rmoraes92/rmoraes92.github.io.git && \
		git add . && \
		git config --local user.email "ramonmoraes.foss@gmail.com" && \
		git config --local user.name "Ramon Moraes" && \
		git commit -m "update" && \
		git push origin -f